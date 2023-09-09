# Visão geral do curso e ferramentas

## Versionamento de código

O versionamento de código é uma prática essencial no desenvolvimento de software que envolve o controle e a gestão das diferentes versões de um código-fonte ao longo do tempo. Ele resolve diversos problemas comuns enfrentados por equipes de desenvolvimento, como colaboração, rastreamento de alterações, recuperação de versões anteriores e garantia de estabilidade do software. O versionamento de código é implementado por meio de sistemas de controle de versão (VCS, Version Control Systems).

**Problemas resolvidos com versionamento de código:**

1. **Controle de Alterações:** O versionamento permite que várias pessoas trabalhem no mesmo código simultaneamente sem conflitos. Ele rastreia quem fez quais alterações e quando, o que facilita a resolução de conflitos.

2. **Recuperação de Versões Anteriores:** Os desenvolvedores podem facilmente voltar a versões anteriores do código se algo der errado ou se desejarem comparar o desempenho de diferentes versões.

3. **Colaboração:** O versionamento de código é essencial para o desenvolvimento colaborativo. Permite que equipes de desenvolvimento em diferentes locais ou fusos horários trabalhem juntas de maneira eficaz.

4. **Testes e Experimentação:** Desenvolvedores podem criar ramos separados (branches) para testar novos recursos ou correções sem afetar o código principal. Isso ajuda a manter a estabilidade do software.

**Sistemas de Controle de Versão (VCS):**

1. **Sistemas de Controle de Versão Centralizados (CVCS):** Nesses sistemas, há um único repositório central onde todo o código é armazenado. Os desenvolvedores fazem check-out (download) do código do repositório central para trabalhar e, em seguida, fazem check-in (upload) para registrar suas alterações. Exemplos de CVCS incluem o Apache Subversion (SVN) e o Microsoft Team Foundation Version Control (TFVC).

2. **Sistemas de Controle de Versão Distribuídos (DVCS):** Em contrapartida, os sistemas de controle de versão distribuídos não têm um repositório central. Cada desenvolvedor tem uma cópia completa do repositório em seu próprio ambiente de desenvolvimento. Isso oferece maior flexibilidade e permite que os desenvolvedores trabalhem offline. Exemplos de DVCS incluem Git e Mercurial.
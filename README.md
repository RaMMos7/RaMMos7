**# Arquivo: miguelfetch.ps1

# Função para escrever em cores
function Write-Color($Text, $Color) {
    Write-Host $Text -ForegroundColor $Color
}

# Banner ASCII colorido
Write-Color "        ██████╗ ██╗    ██╗██╗███╗   ██╗██████╗  ██████╗ ███████╗" "Cyan"
Write-Color "       ██╔═══██╗██║    ██║██║████╗  ██║██╔══██╗██╔═══██╗██╔════╝" "Cyan"
Write-Color "       ██║   ██║██║ █╗ ██║██║██╔██╗ ██║██║  ██║██║   ██║███████╗" "Cyan"
Write-Color "       ██║   ██║██║███╗██║██║██║╚██╗██║██║  ██║██║   ██║╚════██║" "Cyan"
Write-Color "       ╚██████╔╝╚███╔███╔╝██║██║ ╚████║██████╔╝╚██████╔╝███████║" "Cyan"
Write-Color "        ╚═════╝  ╚══╝╚══╝ ╚═╝╚═╝  ╚═══╝╚═════╝  ╚═════╝ ╚══════╝" "Cyan"
Write-Host ""

# Informações pessoais coloridas
Write-Color "Nome: Miguel Ramos dos Santos" "Yellow"
Write-Color "Título: Estagiário/Técnico em TI" "Green"
Write-Color "Experiência: Assistente Técnico na PRF (Atual)" "Green"
Write-Host ""

Write-Color "Educação:" "Magenta"
Write-Color " - Ciências da Computação – Anhanguera (Cursando)" "White"
Write-Color " - Técnico em Informática – SENAI (Cursando)" "White"
Write-Host ""

Write-Color "Habilidades:" "Magenta"
Write-Color " - Linguagens: Python, SQL (MariaDB, MySQL)" "White"
Write-Color " - Ferramentas: Git, Figma, Pacote Office" "White"
Write-Color " - Infraestrutura: Redes TCP/IP, Manutenção de Hardware e Software" "White"
Write-Host ""

Write-Color "Idiomas:" "Magenta"
Write-Color " - Português: Nativo" "White"
Write-Color " - Inglês: Intermediário (B2)" "White"
Write-Color " - Espanhol: Básico (A2)" "White"
**

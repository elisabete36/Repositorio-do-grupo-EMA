# Repositorio-do-grupo-EMA
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADM Barra Lateral</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        /* Estilo para esconder submenus */
        .submenu {
            display: none;
        }
    </style>
</head>
<body class="bg-gray-100">
    <div class="flex">
        <!-- Sidebar -->
        <div class="w-64 bg-green-700 text-white shadow-md h-screen p-4">
            <div class="mb-4">
                <h1 class="text-xl font-bold">ADM</h1>
                <h2 class="text-lg">Barra Lateral</h2>
            </div>
            <ul>
                <!-- Link para a página inicial -->
                <li class="mb-2">
                    <a href="inicio.html" class="flex items-center text-white hover:text-black">
                        <i class="fas fa-home mr-2"></i> Início
                    </a>
                </li>
                <!-- Link para a página CAD Lab -->
                <li class="mb-2">
                    <a href="cadlab.html" class="flex items-center text-white hover:text-black">
                        <i class="fas fa-flask mr-2"></i> CAD Lab
                    </a>
                </li>
                <!-- Gerenciamento com submenu -->
                <li class="mb-2">
                    <a href="#" class="text-white hover:text-black" onclick="toggleSubmenu('gerenciamento')">Gerenciamento</a>
                    <ul id="gerenciamento" class="submenu ml-4 mt-2">
                        <li class="mb-1">
                            <a href="eng-eletrica.html" class="text-white hover:text-black">Eng. Elétrica</a>
                        </li>
                        <li class="mb-1">
                            <a href="equipamento.html" class="text-white hover:text-black">Equipamento</a>
                        </li>
                        <li class="mb-1">
                            <a href="produtos.html" class="text-white hover:text-black">Produtos</a>
                        </li>
                        <li class="mb-1">
                            <a href="materiais-consumo.html" class="text-white hover:text-black">Materiais de Consumo</a>
                        </li>
                        <li class="mb-1">
                            <a href="eng-civil.html" class="text-white hover:text-black">Eng. Civil</a>
                        </li>
                        <li class="mb-1">
                            <a href="eng-software.html" class="text-white hover:text-black">Eng. de Software</a>
                        </li>
                        <li class="mb-1">
                            <a href="ads.html" class="text-white hover:text-black">ADS</a>
                        </li>
                    </ul>
                </li>
                <!-- Gerenciamento de Aula com submenu -->
                <li class="mb-2">
                    <a href="#" class="text-white hover:text-black" onclick="toggleSubmenu('gerenciamentoAula')">Gerenciamento de Aula</a>
                    <ul id="gerenciamentoAula" class="submenu ml-4 mt-2">
                        <li class="mb-1">
                            <a href="requerimento.html" class="text-white hover:text-black">Requerimento</a>
                        </li>
                        <li class="mb-1">
                            <a href="manutencao.html" class="text-white hover:text-black">Manutenção</a>
                        </li>
                        <li class="mb-1">
                            <a href="abrir-chamado.html" class="text-white hover:text-black">Abrir Chamado</a>
                        </li>
                    </ul>
                </li>
                <!-- Link para Estoque/Inventário -->
                <li class="mb-2">
                    <a href="estoque-inventario.html" class="text-white hover:text-black">Estoque/Inventário</a>
                </li>
                <!-- Link para Agendamento de Laboratório -->
                <li class="mb-2">
                    <a href="agendamento-laboratorio.html" class="text-white hover:text-black">Agendamento de Laboratório</a>
                </li>
                <!-- Gerenciamento com submenu -->
                <li class="mb-2">
                    <a href="#" class="text-white hover:text-black" onclick="toggleSubmenu('gerenciamentoAcessos')">Gerenciamento</a>
                    <ul id="gerenciamentoAcessos" class="submenu ml-4 mt-2">
                        <li class="mb-1">
                            <a href="acessos.html" class="text-white hover:text-black">Acessos</a>
                        </li>
                        <li class="mb-1">
                            <a href="novo-acesso.html" class="text-white hover:text-black">Novo Acesso</a>
                        </li>
                        <li class="mb-1">
                            <a href="alterar-cadastro.html" class="text-white hover:text-black">Alterar Cadastro</a>
                        </li>
                        <li class="mb-1">
                            <a href="adicionar-item.html" class="text-white hover:text-black">Adicionar Item</a>
                        </li>
                    </ul>
                </li>
                <!-- Link para Calendário -->
                <li class="mb-2">
                    <a href="calendario.html" class="text-white hover:text-black">Calendário</a>
                </li>
                <!-- Link para Notificação -->
                <li class="mb-2">
                    <a href="notificacao.html" class="text-white hover:text-black">Notificação</a>
                </li>
                <!-- Link para Suporte -->
                <li class="mb-2">
                    <a href="suporte.html" class="text-white hover:text-black">Suporte</a>
                </li>
            </ul>
        </div>
        <!-- Main Content -->
        <div class="flex-1 p-4">
            <h1 class="text-2xl font-bold mb-4 text-green-700">Collab</h1>
            <div class="border p-4 bg-white">
                <h2 class="text-xl font-bold mb-2 text-green-700">Em andamento</h2>
                <p class="mb-2 text-black">Cursos, disciplinas</p>
                <p class="mb-2 text-black">Aparece os cursos para solicitar material</p>
                <h2 class="text-xl font-bold mb-2 text-green-700">Data e Hora de Serviço Realizado</h2>
                <p class="mb-2 text-black">Gráfico de manutenções</p>
                <p class="mb-2 text-black">Histórico de manutenção</p>
                <p class="mb-2 text-black">Manutenção agendada</p>
                <p class="mb-2 text-black">Compra de materiais</p>
            </div>
            <div class="border p-4 bg-white mt-4">
                <h2 class="text-xl font-bold mb-2 text-green-700">Adicionar Estoque</h2>
                <form action="adicionar-estoque.html" method="POST">
                    <div class="mb-4">
                        <label for="item" class="block text-black mb-2">Item</label>
                        <input type="text" id="item" name="item" class="w-full p-2 border border-gray-300 rounded">
                    </div>
                    <div class="mb-4">
                        <label for="quantidade" class="block text-black mb-2">Quantidade</label>
                        <input type="number" id="quantidade" name="quantidade" class="w-full p-2 border border-gray-300 rounded">
                    </div>
                    <div class="mb-4">
                        <label for="descricao" class="block text-black mb-2">Descrição</label>
                        <textarea id="descricao" name="descricao" class="w-full p-2 border border-gray-300 rounded"></textarea>
                    </div>
                    <button type="submit" class="bg-green-700 text-white px-4 py-2 rounded hover:bg-green-800">Adicionar</button>
                </form>
            </div>
        </div>
    </div>
    <script>
        // Função para alternar a exibição dos submenus
        function toggleSubmenu(id) {
            var submenu = document.getElementById(id);
            if (submenu.style.display === "none" || submenu.style.display === "") {
                submenu.style.display = "block";
            } else {
                submenu.style.display = "none";
            }
        }
    </script>
</body>
</html>

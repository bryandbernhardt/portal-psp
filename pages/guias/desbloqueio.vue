<template>
  <main class="md:container mx-auto px-4 py-10">
    <h1 class="text-3xl text-center">Desbloqueio ARK-4</h1>
    <h2 class="text-xl py-4">Porque o ARK-4?</h2>
    <p class="pb-4">
      O motivo que utilizamos o ARK-4 é por ser um desbloqueio que está sendo atualizado até a data de hoje, é mais estável e com maior compatibilidade com os jogos de PSP, além de ser o mais fácil de instalar e remover, ficando de forma isolada do sistema no memory stick. Além de ter a opção de atualizar o desbloqueio de forma online, da mesma forma que fazemos no sistema do PSP original.
    </p>
    <h2 class="text-xl py-4">Instalação</h2>
    <p>
      Para instalar o ARK-4, vou deixar o <a class="underline" href="https://github.com/PSP-Archive/ARK-4" target="_blank" rel="noopener noreferrer">link do repositório oficial</a> que contém a versão disponível mais atualizada. Entrando no repositório, basta clicar nas Releases no lado direito da tela e baixar o arquivo ZIP.
    </p>
    <p>
      Após baixar, é só descompactar o arquivo zip e abrir o arquivo de text README.TXT que contém o passo a passo de como instalar e configurar o ARK-4.
    </p>
    <p class="mt-3">O passo a passo apresentado é basicamente:</p>
    <ol class="list-decimal ml-10">
      <li>Caso o PSP não esteja na versão 6.61, conecte o PSP na internet a vá na opção de atualizar de forma online nas configurações.</li>
      <li>Com o PSP atualizado, conecte o PSP ou o memory stick no computador e siga com a instalação do ARK</li>
      <li>Copiar a pasta 'ARK_01234' para /PSP/SAVEDATA/</li>
      <li>Copiar a pasta 'ARK_Loader' para /PSP/GAME/</li>
      <li>Acessar os jogos do memory stick e abrir o 'ARK Loader'</li>
    </ol>
    <p class="mt-3">Para não precisar rodar o 'Ark Loader' sempre quando ligar o PSP, utilize o Infinity:</p>
    <ol class="list-decimal ml-10">
      <li>Copiar o arquivo EBOOT.PBP (ou EBOOT_GO.PBP caso esteja no PSP GO e renomeie ele para EBOOT.PBP após copiar) de dentro da pasta Infinity para /PSP/GAME/UPDATE, caso não exista a pasta UPDATE, crie.</li>
      <li>Acessar os jogos do memory stick e abrir o 'Infinity', pressione X para o PSP realizar a instalação e X novamente para reiniciar.</li>
      <li>Abra o 'Infinity' novamente e clique seta para esquerda, selecione a opção do ARK-4.</li>
      <li>Pressione o botão utilizado para sair dos jogos e X para confirmar.</li>
      <li>Inicie novamente o 'ARK Loader' e pronto.</li>
    </ol>
  </main>
</template>
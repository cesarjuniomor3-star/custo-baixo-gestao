CUSTO BAIXO GESTÃO - PWA v1.0

O que funciona:
- Cadastro, edição, exclusão e pesquisa de vendas, afiliados e inscrições
- Cálculo de comissões a partir de vendas marcadas como Pago e taxa do afiliado
- Indicadores, gráfico dos últimos seis meses, exportação e importação de backup JSON
- Instalação como PWA e uso offline depois do primeiro acesso

IMPORTANTE: Esta é uma versão local. Os dados são guardados no navegador do dispositivo.
Não existe sincronização entre celular e computador, login, servidor, pagamentos reais ou notificações push.
A seção Comissões é calculada automaticamente e NÃO registra comissões efetivamente pagas.

COMO TESTAR NO PC:
1. Extraia o ZIP.
2. Na pasta extraída, abra um terminal e execute: python -m http.server 8080
3. Abra http://localhost:8080 no navegador.

COMO INSTALAR NO CELULAR:
1. Publique os arquivos em uma hospedagem HTTPS (por exemplo, GitHub Pages ou Netlify).
2. Abra a URL no Chrome Android e use menu > Adicionar à tela inicial / Instalar app.
3. No iPhone, abra no Safari > Compartilhar > Adicionar à Tela de Início.

AVISO: Não hospede dados pessoais de clientes em um ambiente público sem autenticação e infraestrutura segura.
O código estático não contém dados de clientes; os registros adicionados ficam no navegador local.
Faça backups regulares usando Exportar dados.

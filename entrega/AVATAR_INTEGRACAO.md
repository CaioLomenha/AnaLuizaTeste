# Teste de apresentador: foto + voz

A sessão não tem ferramenta de animação facial ou sincronização labial. A imagem enviada não foi animada. Para produzir o teste, usar uma ferramenta externa que aceite foto e áudio, como um fluxo de foto-avatar do HeyGen, conforme os recursos disponíveis na sua conta.

## Arquivos de entrada

- Foto do homem enviada pelo cliente no chat.
- `AtalhoCred-voz-para-avatar.wav`: a voz já tratada da montagem atual, sem música. Duração de 36 s, estéreo, 48 kHz, com entrada de 250 ms e pausa final. Não acelerar, cortar silêncios ou regenerar a fala: isso mudaria a sincronização.

## Direção para o teste

“Use a foto fornecida como referência do apresentador e o áudio fornecido como fala. Apresentador profissional brasileiro, olhando para a câmera, com expressão próxima e segura. Sincronização labial natural, piscadas discretas e movimentos sutis de cabeça. Gestos de mãos contidos. Preservar a aparência e as roupas da foto e a atmosfera do escritório. Preferir enquadramento médio, do peito ou da cintura para cima, com espaço para legendas. Câmera estável. Sem textos, legendas, logos, trilha, transições ou efeitos adicionados. Não alterar a duração nem a velocidade do áudio.”

Esta direção é para um eventual campo de instruções de movimento; não é texto de locução. Se a ferramenta não tiver esse campo, usar os controles equivalentes disponíveis, sem acrescentar fala.

## Exportar

Preferir MP4 vertical 1080 × 1920, 30 fps, 36 s. Não recortar o início ou fim. Manter a sincronização do áudio enviado. Caso a plataforma limite resolução ou duração, informar o formato que ela permitir. Conferir os termos e limites da conta antes de gerar.

## Montagem planejada

- 0–4,6 s: apresentador faz o gancho; texto e legendas sobrepostos com respiro.
- 4,6–9,2 s: corte para os gráficos do escritório.
- 9,2–14,87 s: apresentador apresenta a AtalhoCred.
- 14,87–27,17 s: motion explica as quatro etapas; voz continua em off.
- 27,17–33 s: apresentador conclui e convida à análise.
- 33–36 s: marca, domínio e CTA em tela limpa.

Os cortes serão ajustados após inspecionar o vídeo do avatar. Na integração, usar apenas a imagem do clipe e manter a mixagem já sincronizada, evitando voz duplicada. Enviar o MP4 gerado no chat para integrar ao projeto.

## Alteração já executada

O rótulo “REPRESENTAÇÃO ILUSTRATIVA” foi removido dos quatro cards. A V4 sem esse rótulo mantém voz, legendas e gráficos; ainda não contém apresentador animado.

# Segmentação de vídeos por trechos de fala utilizando redes neurais convolucionais

Este repositório apresenta os códigos utilizados para o desenvolvimento do modelo de classificação utilizando rede neural convolucional. O conjunto de dados utilizado contém 587 trechos de vídeo em formato .wmv que posteriormente serão transformados em formato .wav para estudo do som, o conjunto está divido em 6 classes:
  1. Com fala (classificado por 1)
  2. Sem fala (classificado por 0)
  3. Misto (classificado por 2)
  4. Sem fala e ruídos (classificado por 3)
  5. Com fala e ruídos (classificado por 4)
  6. Misto e ruídos (classificado por 5) 

O nome dos arquivos de vídeo tem o seguinte formato (trecho)-(video_id)-(start)-(end)-(class_id).wav

*   Trecho - nome do trecho de cada vídeo levando em conta o vídeo original
*   Video_id - id do vídeo original
*   Star - minutagem inical do trecho levando em conta a minutagem do vídeo original
*   End - minutagem final do trecho levando em conta a minutagem do vídeo original
*   Class_id - id de classificação do trecho

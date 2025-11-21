## laba1
# Выполнено Шариповой А. И., гр. 432Б
### Ход работы:
1. С сайта скачала и установила Dоcker, открыла приложение.
   
  <img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/08c86819-5abb-474d-8871-a632817f9162" />
2. Создала папку *labadevop*, в неё скачала файл *app.py* и *requirements.txt*, в этой же папке создала *Dockerfile*,  С помощью редактора *VS Code* создан код внутри файла, учтен проброс порта 1234.

<img width="609" height="207" alt="image" src="https://github.com/user-attachments/assets/724c7fcc-38e3-441e-88cc-e9b5d822a4e6" />

3. В терминале Docker Desktop собрала образ с помощью команды docker build -t toptishka .

  <img width="1280" height="481" alt="image" src="https://github.com/user-attachments/assets/d335b8f2-0d2a-472e-8116-1763503a0c2c" />
5. Теперь можно запустить контейнер с помощью команды docker run -p 1234:1234 toptishka

  <img width="1126" height="204" alt="image" src="https://github.com/user-attachments/assets/3b63aef8-bc42-470d-984a-f12d411b3cf8" />
6. После перехода по ссылке http://localhost:1234/, можно увидеть надпись:

<img width="929" height="275" alt="image" src="https://github.com/user-attachments/assets/77524912-f296-46b2-9d7a-871326f46ec4" />
  
7. Следующим этапом было создание файла docker-compose.yml. В нем были прописаны следующие инструкции:

  <img width="590" height="718" alt="image" src="https://github.com/user-attachments/assets/eae81132-d85f-4332-8b05-30f22add23fe" />
  
8. В терминале был пересобран образ с помощью команды docker build -t toptishka ., и запущен стек с помощью команды docker compose up.

  <img width="1280" height="428" alt="image" src="https://github.com/user-attachments/assets/9a97d1d5-dbd7-44b5-a652-6f70bc3a7f40" />
9. После одновления страницы, можно увидеть надпись:

  <img width="939" height="340" alt="image" src="https://github.com/user-attachments/assets/adf9a8a4-b61f-4611-8189-d5a256543316" />
  
---

# Заключение
#### В ходе лабораторной работы были изучены основы контейнеризации с использованием *Docker*. Были освоены команды для управления контейнерами и образами, а также изучена надстройка *Docker-compose*, с помощью которой можно было запускать стек контейнеров.


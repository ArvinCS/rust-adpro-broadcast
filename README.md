### Result

![1 server and 3 clients](asset/cmd.png)

Client dapat mengirimkan pesan ke server. Kemudian, server menerima pesan dan membagikannya ke client lainnya dalam bentuk broadcast. Maka dari itu, ketika client mengirim pesan maka client lainnya dapat melihatnya. 

![1 server and 3 clients after modify port](asset/cmd2.png)

Ketika ingin mengubah host atau port dari websocket yang kita punya, maka client dan server harus dipastikan sudah merubah tempat mereka menerima pesan tersebut. Dengan kata lain, server dan client harus menggunakan websocket di tempat yang sama. Jika tidak, maka client tidak akan bisa terhubung ke server. 
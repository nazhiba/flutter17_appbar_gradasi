# flutter17_appbar_gradasi

A new Flutter project.

> Penggunaan :

- leading = digunakan untuk menambahkan ```aksi/tombol/icon``` pada sudut kiri dari ```AppBar```

```leading: Icon(
            Icons.adb,
            color: Colors.white,
          ),```

- Action = Digunakan untuk menambahkan widget aksi seperti tombol, teks, atau widget lainnya

```actions: [
            IconButton(onPressed: () {}, icon: Icon(Icons.settings)),
            IconButton(onPressed: () {}, icon: Icon(Icons.exit_to_app)),
          ],```

- FlexibleSpace = Digunakan untuk menampilkan widget di bagian ```AppBar``` seperti gambar latar belakang, gradien, atau dekorasi

```flexibleSpace: Container(
            decoration: BoxDecoration(
                gradient: LinearGradient(
                    colors: [Color(0xff0096ff), Color(0xff661062)],
                    begin: FractionalOffset.topLeft,
                    end: FractionalOffset.bottomRight),
                
                
                // image: DecorationImage(
                //     image: AssetImage("gambar/index.jpg"),
                //     fit: BoxFit.none,
                //     repeat: ImageRepeat.repeat)
                ),
          ),```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

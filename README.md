# Selamat datang di State Management saya, agar kode berjalan dengan baik pastikan anda sudah memiliki :
Dart (bahasa pemrograman open-source yang dikembangkan oleh Google. Dart digunakan untuk mengembangkan aplikasi web, seluler, dan sisi server.)
SDK Flutter (Untuk menjalankan Framework Dart yang bernama Flutter)

# Penggunaan File Ini

1. Memodifikasi File Main
   Agar kode berjalan sesuai yang user inginkan anda bisa memilih antara ingin mencoba file stateless ataupun file stateful
   dengan merubah
     void main() {
    runApp(MyStatefulWidgetApp());

- MyStatefulWidgetApp = untuk menjalankan file Stateful.
- MyStatelessApp = untuk menjalankan kode stateless

2. Memodifikasi file pada test/widget_test.dart
   Setelah memilih ingin mencoba MyStatefulWidgetApp atau MyStatelessApp, anda juga harus menyesuaikan file test sesuai dengan yang anda gunakan pada file main fucntion anda
   void main() {
  testWidgets('Counter increments smoke test', (WidgetTester tester) async {
    // Build our app and trigger a frame.
    await tester.pumpWidget(MyStatefulWidgetApp()); //Spesifik pada bagian ini

   Anda dapat menyesuaikan dengan tipe widget yang anda gunakan


# Mengenai Perbedaan Stateful dan Stateless

## StatelessWidget
Penjelasan : Widget ini bersifat statis, artinya tampilannya tidak berubah selama siklus hidup widget.'

## StatefulWidget
Penjelasan : Widget ini bersifat dinamis, artinya tampilannya dapat berubah selama siklus hidup aplikasi berdasarkan perubahan data atau interaksi pengguna.

# Perbedaan Antara Kode Stateful dan Stateless

Pada bagian StatefulWidget tampilan dapat berubah sesuai dengan interkasi user seperti perubahan angka pada saat tombol di click, sedangkan pada StatelessWidget tampilan tidak dapat di rubah (Atau biasa disebut dalam mode statis), Yang dimana User tidak dapat berinteraksi pada halaman yang Statis (Menjelaskan mengapa saat tombol di click angka tidak berubah sama skali)


**Sekian Dan terima Kasih **

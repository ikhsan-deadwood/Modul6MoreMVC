Peran Bagian MVC

MVC adalah konsep pembangunan aplikasi berbasis web yang membagi aplikasi web menjadi 3 bagian besar yaitu model, view ,dan controller.

Tujuan

Memahami peran dan fungsi masing-masing bagian MVC.

Tentang Program

    Membuat aplikasi pemesanan makanan.
    Membuat keranjang sebagai wadah makanan dan minuman yang dipesan.
    Bagian yang bertanggung jawab melakukan kalkulasi, diwadahi dalam kelas Payment

How does it works?

logika perhitungan untuk melakukan kalkulasi terdapat pada class Payment.cs
``` class Payment
    {
        private double deliveryFee = 0;
        private double promo = 0;
        private double balance = 0;
        private OnPaymentChangedListener paymentCallback;
```
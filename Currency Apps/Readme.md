# Currency Apps
Aplikasi ini mencakup fungsi perhitungan nilai tukar mata uang dari dollar ke rupiah.
Satu dolar dianggap senilai Rp.15.000

## Scope & Functionalities
- User dapat memasukkan angka
- User dapat menyentuh tombol hitung
- User mendapat info "INVALID" jika yang dimasukkan berupa text

## How Does it works?

Diawali dari method `MainWindow` pada class MainWindow.xaml.cs, 
cara mendeklarasikannya 

```csharp
public MainWindow()
        {
            InitializeComponent();
            currency = new CurrencyController();
        }
``` 

Logika perhitungan terdapat pada class `CurrencyController.cs`sebagai berikut
cara kerjanya blablabla,,,,,
```csharp
public string usdToIdr(string nominal)
        {
            var nominalDouble = Convert.ToDouble(nominal);
            var result = nominalDouble * 15000;
            return Convert.ToString(result);
        }
```

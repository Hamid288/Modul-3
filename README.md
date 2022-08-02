##### Nama : Abdul hamid
##### Kelas : XII RPL 1
##### NO Absen : 02

Langkah Pertama cari folder web.php seperti di bawah ini

![image](https://user-images.githubusercontent.com/109930540/182107706-fb6930e9-5c5b-4ccb-8d4f-056e9a60d578.png)

# MODUL 3
##### Selanjutnya kita akan membuat Route yang akan menuju ke halaman kategori

``` <?php

namespace illuminate\Http\Controllers;

use Illuminate\http\Request;

class BarangController extends Controller
{
    public function index()
    {
        return 'Mengakses Fungsi di controller menggunakan route';
    }

public function add()
{
    return'you';
}           
}
```

dan kita akan membuat kodingan seperti di bawah ini

![image](https://user-images.githubusercontent.com/109930532/182266823-8b0f2a70-678e-4fb2-9b1d-727e704efe8b.png)

dan jangan lupa kita meruning dulu biar kode keluar.


![image](https://user-images.githubusercontent.com/109930532/182266990-05c0ec05-d0d3-4778-95b8-d3cf01856a83.png)

dan kita akan membuka crom di dalam kode "http/127.0.0.1:8000/kategori" dan hasilnya seperti ini.

![image](https://user-images.githubusercontent.com/109930532/182267145-666eed1a-85c4-4388-b1ef-f64906862944.png)

selesaikan tugas modul 3.



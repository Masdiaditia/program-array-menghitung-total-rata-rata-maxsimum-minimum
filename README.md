# program-array-menghitung-total-rata-rata-maxsimum-minimum

    #include <iostream>
    using namespace std;

    // Deklarasi Variabel

    //Array berjumlah 5
    int nilai[5];
    int jml_nilai = 0;
    int rata_rata = 0;
    int nilai_max = 0;
    int nilai_min = 100;

    // Deklarasi Main
    int main()
    {
    cout <<"***************************************" << endl;
    cout <<"Masukkan nilai mahasiswa : "<< endl;
    cout <<"***************************************" << endl;
    // Looping Array
    for (int index=0;index<5;index++)
    {
    //Menginput nilai mahasiswa
    cout << "Nilai Mahasiswa ke –  "<< index+1 << ": ";
    cin >> nilai[index];

    //Menjumlahkan nilai mahasiswa
    jml_nilai = jml_nilai + nilai[index];

    //Membandingkan nilai terbesar
    if (nilai_max < nilai[index])
    {
    nilai_max = nilai[index];
    }

    //Membandingkan nilai terkecil
    else if (nilai_min > nilai[index])
    {
    nilai_min = nilai[1];
    }
    }
    cout <<"***************************************" << endl;
    //Menampilkan jumlah nilai mahasiswa
    cout << "Jumlah nilai mahasiswa \t\t"<<"= " <<jml_nilai << endl;

    //Menghitung rata-rata nilai mahasiswa
    rata_rata = jml_nilai/5;

    //Menampilkan nilai rata mahasiswa
     cout << "Rata-rata nilai mahsiswa \t"<<"= " <<rata_rata << endl;

    //Menampilkan nilai tertinggi mahasiswa
    cout << "Nilai tertinggi mahasiswa \t"<<"= " <<nilai_max << endl;

    //Menampilakn nilai terendah mahasiswa
    cout << "Nilai terendah mahasiswa \t"<<"= " <<nilai_min << endl;
    cout <<"***************************************" << endl;
    }
    
    
 hasil![img](https://github.com/Masdiaditia/program-array-menghitung-total-rata-rata-maxsimum-minimum/blob/master/array%20program%20menghitung%20total,rata-rata,maxsimum,minimum.png?raw=true)

# Merubah-nilai-menjadi-huruf

    #include<iostream>
    using namespace std;
    int main()
    {
    int nilai;
    char indeks;
    cout << "\t\t ================== \n";
    cout << "\t\t Program penilaian \n";
    cout << "\t\t ================== \n";
    cout << "\t\t Masukkan nilai : ";
    cin >> nilai;
    if (nilai>=80)
        indeks='A';
    else
        if ((nilai>=70)&&(nilai<=80))
        indeks='B';
    else
        if ((nilai>=55)&&(nilai<=70))
        indeks='C';
    else
        if ((nilai>=45)&&(nilai<=55))
        indeks='D';
    else
        indeks='E';
    cout << "\t\t Indeks nilai = " << indeks;
    }


## Hasilnya

![img](https://github.com/ernico27/Merubah-nilai-menjadi-huruf/blob/master/nilai%20ke%20huruf.png?raw=true)

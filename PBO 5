class Orang {
    constructor(nama, alamat) {
        this.nama = nama;
        this.alamat = alamat;
    }

    tampilkanInformasi() {
        console.log(`Nama: ${this.nama}, Alamat: ${this.alamat}`);
    }
}

// Definisi kelas turunan
class Mahasiswa extends Orang {
    constructor(nama, alamat, nim) {
        super(nama, alamat); // Memanggil konstruktor kelas induk
        this.nim = nim;
    }

    tampilkanInformasi() {
        super.tampilkanInformasi(); // Memanggil metode dari kelas induk
        console.log(`NIM: ${this.nim}`);
    }
}

// Penggunaan kelas turunan
const mahasiswa1 = new Mahasiswa("Budi", "Jl. Merdeka", "123456");
mahasiswa1.tampilkanInformasi();


===============================================================================

// Definisi kelas induk
class Orang {
    tampilkanPeran() {
        console.log("Peran: Orang biasa");
    }
}

// Definisi kelas turunan
class Mahasiswa extends Orang {
    tampilkanPeran() {
        console.log("Peran: Mahasiswa");
    }
}

class Dosen extends Orang {
    tampilkanPeran() {
        console.log("Peran: Dosen");
    }
}

// Menggunakan polimorfisme
const orang1 = new Orang();
const mahasiswa1 = new Mahasiswa();
const dosen1 = new Dosen();

orang1.tampilkanPeran();    // Output: Peran: Orang biasa
mahasiswa1.tampilkanPeran(); // Output: Peran: Mahasiswa
dosen1.tampilkanPeran();     // Output: Peran: Dosen

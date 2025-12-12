interface Kinerja {
    void deskripsiKerja();
}
class Pegawai {
    private String nama;
    private int usia;
    private String jabatan;

public Pegawai(String nama, int usia, String jabatan) {
    this.nama = nama;
    this.usia = usia;
    this.jabatan = jabatan;
    }
public String getNama() {
        return nama;
    }
public void setNama(String nama) {
        this.nama = nama;
    }
public int getUsia() {
        return usia;
   }
public void setUsia(int usia) {
        this.usia = usia;
    }
public String getJabatan() {
        return jabatan;
   }
public void setJabatan(String jabatan) {
        this.jabatan = jabatan;
    }
}

 class PegawaiTetap extends Pegawai implements Kinerja {
public PegawaiTetap(String nama, int usia, String jabatan) {
    super(nama, usia, jabatan);
    }

public void deskripsiKerja() {
    System.out.println("Pegawai tetap bekerja full time.");
    }
}
class PegawaiKontrak extends Pegawai implements Kinerja {
    public PegawaiKontrak(String nama, int usia, String jabatan) {
        super(nama, usia, jabatan);
    }
    public void deskripsiKerja() {
        System.out.println("Pegawai kontrak bekerja sesuai waktu perjanjian.");
    }
}
public class UasPboBiodataPegawai {
    public static void main(String[] args) {

        PegawaiTetap A = new PegawaiTetap("Ilona", 15, "Programmer");
        PegawaiKontrak B = new PegawaiKontrak("Naura", 15, "Development");
        System.out.println("=== Pegawai Tetap ===");
        System.out.println("Nama     : " + A.getNama());
        System.out.println("Usia     : " + A.getUsia());
        System.out.println("Jabatan  : " + A.getJabatan());
       A.deskripsiKerja();

        System.out.println("\n=== Pegawai Kontrak ===");
        System.out.println("Nama     : " + B.getNama());
        System.out.println("Usia     : " + B.getUsia());
        System.out.println("Jabatan  : " + B.getJabatan());
       B.deskripsiKerja();
    }
}
import java.util.Scanner;

public class TugasPercabangan {

    public static void main(String[] args) {
        // Membuat scanner untuk input dari user
        Scanner scanner = new Scanner(System.in);

        // Deklarasi variabel
        int gajiPokok = 5000000;
        double gajiAkhir, tambahan;
        int uangLemburPerJam = 50000;
        int jamLembur, masaKerja, jamKerja;

        System.out.print("Masukkan masa kerja (dalam tahun): 12 ");
        masaKerja = scanner.nextInt(12);
        System.out.print("Masukkan total jam kerja dalam 1 bulan: 8 ");
        jamKerja = scanner.nextInt(8);

        if (jamKerja > 40) { // 240 jam = 8 jam/hari * 30 hari
            jamLembur = jamKerja - 40;
        } else {
            jamLembur = 0;
        }

        if (masaKerja < 5) {
            tambahan = 0;
        } else if (masaKerja >= 5 && masaKerja <= 10) {
            tambahan = gajiPokok * 0.05; // Tambahan 5%
        } else {
            tambahan = gajiPokok * 0.10; // Tambahan 10%
        }

        // Hitung gaji akhir
        gajiAkhir = gajiPokok + tambahan + (uangLemburPerJam * jamLembur);

        // Tampilkan hasil perhitungan
        System.out.println("Gaji pokok: Rp.5.000.000 " + gajiPokok);
        System.out.println("Tambahan gaji: Rp.1.000.000 " + tambahan);
        System.out.println("Uang lembur: Rp.500.000 " + uangLemburPerJam * jamLembur);
        System.out.println("Gaji total yang diterima: Rp4.500.000 " + gajiAkhir);

        scanner.close();
    }
}
// Deklarasi
// Var gajiPokok = 5000000;
// uangLembur = 50000;
// masaKerja;
// jamKerja;
// jumlahJamKerja;
// jumlahJamLembur;
// : integer;
// totalGaji;
// bonus;
// : double;

// Algoritma
// input(masaKerja);
// input(jamKerja);
// if (masa kerja <5 tahun) then
// output (bonus = 0);
// else if (masa kerja>= 5 && masaKerja <= 10 ) then
// output (bonus = 0,05 *uangLembur);
// else(masa kerja > 10 tahun) then
// output (bonus = 0,01)

// End

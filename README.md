# fandhiakhmad
Fandhi Akhmad 5214100171 PSO E Sistem Informasi Institut Teknologi Sepuluh Nopember



public class Bata{
	public static void main(String[] args) {
	String bata = "[ == ]";
	int baris , kolom;
	
	for (baris = 0;baris < 10;baris++){
	for (kolom = 0;kolom < 10;kolom++){
	
	System.out.print(bata);
	}
	System.out.println();}
	}
}

public class Namateman {
	public static void main(String[] adhen) {
	
		String[] teman = new String[10];
		
		teman [0] = "Syahrul";
		teman [1] = "Fata";
		teman [2] = "Adhen";
		teman [3] = "Wasis";
		teman [4] = "Fachrur";
		teman [5] = "Oman";
		teman [6] = "Zul";
		teman [7] = "Putra";
		teman [8] = "Adi";
		teman [9] = "Umar";
		
		for(int i=0;i<teman.length;i++) {
			System.out.println("Nama ke-" + (i+1) + teman[i]);
		}
	}
	
	import java.util.Scanner;
import java.util.Calendar;

public class NRP5214100171 {
	public static void main(String[] args) {
	
		Scanner aku   = new Scanner(System.in);
		Calendar kamu = Calendar.getInstance();
		String nama, nip, tahun, bulan, tanggal, tahunkerja, bulankerja, jeniskelamin;
		
		System.out.println(" ");
		System.out.println("===============================");
		System.out.println("WELCOME TO NIP DATABASE PROGRAM");
		System.out.println("===============================");
		System.out.println(" ");
		
		System.out.print("Nama = ");
		nama = aku.nextLine();
		System.out.print("NIP  = ");
		nip  = aku.nextLine();
		
		tahun        = nip.substring(0, 4);
		bulan        = nip.substring(4, 6);
		tanggal      = nip.substring(6, 8);
		tahunkerja   = nip.substring(8, 12);
		bulankerja   = nip.substring(12, 14);
		jeniskelamin = nip.substring(14,15);
		
		int bln = Integer.parseInt(bulan);
				if (bln==1) {
					bulan= "Januari";
					}
				else if (bln==2) {
					bulan= "Februari";
					}
				else if (bln==3) {
					bulan= "Maret";
					}
				else if (bln==4) {
					bulan= "April";
					}
				else if (bln==5) {
					bulan= "Mei";
					}
				else if (bln==6) {
					bulan= "Juni";
					}
				else if (bln==7) {
					bulan= "Juli";
					}
				else if (bln==8) {
					bulan= "Agustus";
					}
				else if (bln==9) {
					bulan= "September";
					}
				else if (bln==10) {
					bulan= "Oktober";
					}
				else if (bln==11) {
					bulan= "November";
					}
				else if (bln==12) {
					bulan= "Desember";
					}
				else{
				    bulan = "NIP Yang Anda Masukkan Salah";
					}
					
		int jk = Integer.parseInt(jeniskelamin);
				if (jk == 1) {
					jeniskelamin = "Pria";
					}
				else if (jk == 2) {
					jeniskelamin = "Wanita";
					}
				else{
					jeniskelamin = "Spesies lain";
					}
					
		int blnkrj = Integer.parseInt(bulankerja);
				if (blnkrj==1) {
					bulankerja = "Januari";
					}
				else if (blnkrj==2) {
					bulankerja = "Februari";
					}
				else if (blnkrj==3) {
					bulankerja = "Maret";
					}
				else if (blnkrj==4) {
					bulankerja = "April";
					}
				else if (blnkrj==5) {
					bulankerja = "Mei";
					}
				else if (blnkrj==6) {
					bulankerja = "Juni";
					}
				else if (blnkrj==7) {
					bulankerja = "Juli";
					}
				else if (blnkrj==8) {
					bulankerja = "Agustus";
					}
				else if (blnkrj==9) {
					bulankerja = "September";
					}
				else if (blnkrj==10) {
					bulankerja = "Oktober";
					}
				else if (blnkrj==11) {
					bulankerja = "November";
				}
				else if (blnkrj==12) {
					bulankerja = "Desember";
				}
				else{
					bulankerja = "NIP Yang Anda Masukkan Salah";
					}
					
		int umur      = (kamu.get(Calendar.YEAR)) - Integer.parseInt (tahun);
		int lamakerja = (kamu.get(Calendar.YEAR)) - Integer.parseInt (tahunkerja);
			
			System.out.println();
			System.out.println("\t=====================");
			System.out.println("\tIDENTITAS PEMILIK NIP");
			System.out.println("\t=====================");
			System.out.println();
			System.out.println("Nama          = " +nama);
			System.out.println("NIP           = " +nip);
			System.out.println("Tanggal Lahir = " +tanggal+ " " +bulan+ " " +tahun);
			System.out.println("Umur          = " +umur+ " Tahun ");
			System.out.println("Jenis Kelamin = " +jeniskelamin);
			System.out.println("Tahun Kerja   = " +bulankerja+ " " +tahunkerja);
			System.out.println("Lama Jabatan  = " +lamakerja+ " Tahun ");
	}
}

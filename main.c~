//#include <stdio.h>
//#include <stdlib.h>
//#include <string.h>
// test comment
//struct mahasiswa{
//    char nama[25];
//    char nim[10];
//    int skslulus;
//};
//
//struct nilai{
//    char nim[10];
//    char namaMK[10];
//    int sks;
//    int uts;
//    int uas;
//    int hadir;
//    char indeks;
//};
//
//struct mahasiswa mhs[]={};
//
//struct nilai nil[]={
//};
//
//void isimhs(){
//    int n = 4;
//    FILE *Datamhs = fopen("Mahasiswa.txt", "w");
//    strcpy(mhs[0].nama,"Budi Banjaran");
//    strcpy(mhs[0].nim,"101");
//    strcpy(mhs[1].nama,"Cici Cianjuran");
//    strcpy(mhs[1].nim,"102");
//    strcpy(mhs[2].nama,"Bandung Bondowoso");
//    strcpy(mhs[2].nim,"103");
//    strcpy(mhs[3].nama,"Dudi Durudi");
//    strcpy(mhs[3].nim,"104");
//
//    if (Datamhs == NULL) {
//        printf("Error membuka file!\n");
//        return;
//    }
//    int i =0;
//    while(fwrite(mhs[i],sizeof(mhs[i]),1,Datamhs)){
//        i++;
//    };
//    fclose(Datamhs);
//
//};
//
////void isinilai(){
////    int m = 11;
////    FILE *Datanil = fopen("Nilai.txt", "w");
////    if (Datanil == NULL) {
////        printf("Error membuka file!\n");
////        return;
////    }
////    fprintf(Datanil,"101 Fisika 3 80 85 70\n102 Fisika 3 70 60 85\n101 Fisika 3 40 35 90\n101 Kalkulus 4 30 30 80\n102 Kalkulus 4 50 100 80\n103 Kalkulus 4 60 65 75\n104 Kalkulus 4 90 70 80\n101 Agama 2 90 80 75\n102 Agama 2 75 60 90\n103 Agama 2 100 100 70\n104 Agama 2 50 45 90");
////    fclose(Datanil);
////
////};
//
//void buatarray(char mode){
//    if (mode == 'a'){
//        FILE *fp = fopen("Mahasiswa.txt", "r");
//        int n = 4;
//        if (fp == NULL) {
//            printf("Error membuka file!\n");
//            return;
//        }
//        int i = 0;
//        while(fread(mhs[i],sizeof(mhs[i]),1,fp)){
//            i++;
//        };
//        fclose(fp);
//    }
////    else {
////        FILE *tp=fopen("Nilai.txt","r");
////        if (tp == NULL) {
////            printf("Error membuka file!\n");
////            return;
////        }
////        int i=0;
//////        while (fread(tp, "%s %s %d %d %d %d", &nil[i].nim, &nil[i].namaMK, &nil[i].sks, &nil[i].uts, &nil[i].uas, &nil[i].hadir)) {
//////            i++;
//////        }
////        fclose(tp);
////    };
//};
//
//
//
//void tampil(){
//    int n = 4;
//    for(int i = 0; i < n; i++){
//        printf("%s %s\n",mhs[i].nama,mhs[i].nim);
//    }
//};
////void tampil2(){
////    int n = 4;
////    for(int i = 0; i < n; i++){
////        printf("%s %s\n",nil[i].nim, nil[i].namaMK, nil[i].sks, nil[i].uts, nil[i].uas, nil[i].hadir);
////    }
////};
//
//void identitas(){
//    printf("Nama : Muhammad Fakhri Arrasyid\nKelas : TK 47-04\nNIM : 101032300150\nKode Soal : PAX1Y2Z3124F1Z\n\n");
//};
//
//int main(){
//    identitas();
//    isimhs();
////    isinilai();
//    buatarray('a');
////    buatarray('b');
//    tampil();
////    tampil2();
//
//    return 0;
//}
//
//#include <stdio.h>
//#include <stdlib.h>
//#include <string.h>
//
//struct mahasiswa {
//    char nama[25];
//    char nim[10];
//    int skslulus;
//};
//
//struct nilai {
//    char nim[10];
//    char namaMK[10];
//    int sks;
//    int uts;
//    int uas;
//    int hadir;
//    char indeks;
//};
//
//struct mahasiswa mhs[];
//
//struct nilai nil[] = {};
//
//void isimhs() {
//    FILE *Datamhs = fopen("Mahasiswa.txt", "w");
//
//    if (Datamhs == NULL) {
//        printf("Error membuka file!\n");
//        return;
//    }
//
//    strcpy(mhs[0].nama, "Budi Banjaran");
//    strcpy(mhs[0].nim, "101");
//    mhs[0].skslulus = 0;
//
//    strcpy(mhs[1].nama, "Cici Cianjuran");
//    strcpy(mhs[1].nim, "102");
//    mhs[1].skslulus = 0;
//
//    strcpy(mhs[2].nama, "Bandung Bondowoso");
//    strcpy(mhs[2].nim, "103");
//    mhs[2].skslulus = 0;
//
//    strcpy(mhs[3].nama, "Dudi Durudi");
//    strcpy(mhs[3].nim, "104");
//    mhs[3].skslulus = 0;
//
//    for (int i = 0; i < 4; i++) {
//        fwrite(&mhs[i], sizeof(mhs[i]), 1, Datamhs);
//    }
//
//    fclose(Datamhs);
//}
//
//// void isinilai() {
////     // Bagian ini dimatikan sesuai instruksi
//// }
//
//void buatarray(char mode) {
//    if (mode == 'a') {
//        FILE *fp = fopen("Mahasiswa.txt", "r");
//
//        if (fp == NULL) {
//            printf("Error membuka file!\n");
//            return;
//        }
//
//        for (int i = 0; i < 4; i++) {
//            fread(&mhs[i], sizeof(struct mahasiswa), 1, fp);
//        }
//
//        fclose(fp);
//    }
//    // else {
//    //     // Bagian ini dimatikan sesuai instruksi
//    // }
//}
//
//void tampil() {
//    for (int i = 0; i < 4; i++) {
//        printf("%s %s\n", mhs[i].nama, mhs[i].nim);
//    }
//}
//
//// void tampil2() {
////     // Bagian ini dimatikan sesuai instruksi
//// }
//
//void identitas() {
//    printf("Nama : Muhammad Fakhri Arrasyid\nKelas : TK 47-04\nNIM : 101032300150\nKode Soal : PAX1Y2Z3124F1Z\n\n");
//}
//
//int main() {
//    identitas();
//    isimhs();
//    // isinilai();
//    buatarray('a');
//    // buatarray('b');
//    tampil();
//    // tampil2();
//
//    return 0;
//}
#include <stdio.h>   // Untuk fungsi input/output standar
#include <stdlib.h>  // Untuk fungsi malloc, realloc, dan free
#include <string.h>  // Untuk fungsi strtok dan strcmp
#include <ctype.h>   // Untuk fungsi tolower

// Struktur untuk menyimpan kata dan frekuensinya
typedef struct {
    char *word;
    int count;
} WordCount;

int main() {
    WordCount *wordCounts = NULL;  // Array dinamis untuk menyimpan kata dan frekuensi
    int uniqueWords = 0;           // Jumlah kata unik
    char *input = NULL;            // Buffer untuk input
    size_t len = 0;                // Panjang buffer (akan diatur oleh getline)
    ssize_t read;                  // Jumlah karakter yang dibaca

    printf("Masukkan teks (tekan Enter dua kali untuk selesai):\n");

    // Loop untuk membaca input
    while ((read = getline(&input, &len, stdin)) != -1 && input[0] != '\n') {
        char *word = strtok(input, " \t\n");  // Memisahkan kata pertama
        while (word != NULL) {
            // Mengubah kata menjadi huruf kecil
            for (int i = 0; word[i]; i++) {
                word[i] = tolower(word[i]);
            }

            int found = 0;
            // Mencari apakah kata sudah ada dalam array
            for (int i = 0; i < uniqueWords; i++) {
                if (strcmp(wordCounts[i].word, word) == 0) {
                    wordCounts[i].count++;  // Jika ada, tambah frekuensi
                    found = 1;
                    break;
                }
            }

            // Jika kata baru, tambahkan ke array
            if (!found) {
                wordCounts = realloc(wordCounts, (uniqueWords + 1) * sizeof(WordCount));
                wordCounts[uniqueWords].word = strdup(word);
                wordCounts[uniqueWords].count = 1;
                uniqueWords++;
            }

            word = strtok(NULL, " \t\n");  // Ambil kata berikutnya
        }
    }

    // Menampilkan hasil
    printf("\nFrekuensi kata:\n");
    for (int i = 0; i < uniqueWords; i++) {
        printf("%s: %d\n", wordCounts[i].word, wordCounts[i].count);
        free(wordCounts[i].word);  // Bebaskan memori untuk setiap kata
    }
    free(wordCounts);  // Bebaskan array wordCounts
    free(input);       // Bebaskan buffer input

    return 0;
}

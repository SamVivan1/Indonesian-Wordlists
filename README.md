## Bahasa Indonesia

### **Deskripsi**
Indonesian Word List ini adalah kumpulan kata-kata dalam bahasa Indonesia yang dapat digunakan untuk tujuan penelitian keamanan, khususnya untuk password bruteforce. Daftar kata ini terdiri dari kata-kata umum dalam bahasa Indonesia yang bisa digunakan untuk melakukan serangan brute force pada sistem password yang menggunakan bahasa Indonesia sebagai sumber kata sandi.

**⚠️ Peringatan:**
Penggunaan alat ini hanya diperuntukkan untuk tujuan yang sah dan etis, seperti pengujian penetrasi yang diotorisasi atau riset keamanan. Penyalahgunaan dapat melanggar hukum yang berlaku di wilayah hukum Anda. Pastikan Anda memiliki izin sebelum melakukan pengujian terhadap sistem apa pun.

### **Struktur File**
- `indonesian_wordlist.txt`: File utama yang berisi daftar kata dalam bahasa Indonesia.
  
### **Penggunaan**
1. Unduh atau klon repository ini.
2. File `indonesian_wordlist.txt` dapat digunakan sebagai input untuk alat-alat bruteforce seperti:
   - **Hydra**
   - **John the Ripper**
   - **Hashcat**
3. Integrasikan daftar kata ini dengan alat keamanan yang Anda gunakan untuk menguji kekuatan password pada target.

Contoh penggunaan di Hydra:

```bash
hydra -l [username] -P indonesian_wordlist.txt [target_ip] [service]
```
---

## English

### **Description**
This Indonesian Word List is a collection of Indonesian words designed for security research purposes, particularly for password brute-forcing. The word list consists of common Indonesian words that can be used to perform brute force attacks on password systems that use the Indonesian language as a source for passwords.

**⚠️ Warning:**
This tool is intended solely for legitimate and ethical purposes, such as authorized penetration testing or security research. Misuse of this tool may violate laws in your jurisdiction. Ensure you have proper authorization before testing any system.

### **File Structure**
- `indonesian_wordlist.txt`: The main file containing a list of words in the Indonesian language.

### **Usage**
1. Download or clone this repository.
2. The `indonesian_wordlist.txt` file can be used as input for brute-force tools such as:
   - **Hydra**
   - **John the Ripper**
   - **Hashcat**
3. Integrate this word list into your security tools to test password strength on your target.

Example usage with Hydra:

```bash
hydra -l [username] -P indonesian_wordlist.txt [target_ip] [service]
```

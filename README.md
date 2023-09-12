# GUIDE
1. **Fork** repository
   
3. **Clone** repository
   
   ```sh
   
   git clone https://github.com/Username Github/LABBD23
   
   ```
4. Branch making with **NIM**
   
   ```sh
   
   cd LABBD23
   git branch NIM
   git checkout NIM
   
   mkdir NIM
   cd NIM
   
   ```
   
5. Task submitted by each folder, n(INT) = corresponding chapter
   
   ```sh
   
   mkdir "Pn"
   cd "Pn"
   
   ```
   
6. **commit** task
   
   ```sh
   
   #menambahkan seluruh file sekaligus
   git add .
   
   #memilih file tertentu
   git add "file_name"
   
   git commit -m "Commit message"
   
   ```
   
7. **push** task
    
   ```sh
   
   git push origin NIM
   
   ```
   
8. Go to **Pull request** tab and submit by doing pull request

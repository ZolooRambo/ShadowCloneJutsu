# Лабораторийн ажил: Git Clone, Commit, Push, Pull ашиглах

## 1. Түлхүүр үг
Git, GitHub, repository, clone, commit, push, pull, remote repository, local repository, version control

## 2. Хичээлийн зорилго
Оюутнуудад GitHub дээр байрлах repository-г локаль компьютер дээр clone хийх, локаль дээр өөрчлөлт хийх, commit хийх, GitHub руу push хийх болон GitHub дээрх шинэ өөрчлөлтийг pull хийх процессыг ойлгуулах.

## 3. Суралцах үр дүн
Энэхүү лабораторийн ажлыг хийсний дараа оюутан дараах чадваруудыг эзэмшинэ:
1. GitHub repository-г локаль компьютерт clone хийх  
2. Локаль repository дээр файл өөрчлөх  
3. `git add` болон `git commit` ашиглах  
4. Өөрчлөлтүүдийг GitHub руу `git push` ашиглан илгээх  
5. GitHub дээрх шинэ өөрчлөлтийг `git pull` ашиглан татах  

## 4. Хэрэглэх программ хангамж
- Git  
- Git Bash  
- GitHub account  
- Интернэт холболт  

## 5. Онолын үндэс
Git бол Version Control System буюу файлын өөрчлөлтийг хянах систем юм. GitHub нь Git дээр суурилсан онлайн repository хадгалах платформ юм.  
- Local repository – хэрэглэгчийн компьютер дээр байрлана.  
- Remote repository – интернет дээр (GitHub) байрлана.  

## 6. Git командуудын тайлбар
- `git clone` – GitHub дээрх repository-г локаль компьютерт татах  
- `git add` – өөрчлөгдсөн файлуудыг staging area-д нэмэх  
- `git commit` – өөрчлөлтийг version history-д хадгалах  
- `git push` – локаль commit-уудыг GitHub руу илгээх  
- `git pull` – GitHub дээрх шинэ commit-уудыг локаль repository руу татах  

## 7. Лабораторийн ажлын заавар
1. GitHub дээр repository үүсгэх  
2. Repository URL авах  
3. Repository-г clone хийх  
   ```bash
   git clone https://github.com/username/repository.git

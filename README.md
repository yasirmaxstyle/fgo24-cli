# Mini-task CLI usage

This is a bare-minimum usage of CLI according to mini task on **Day 1** (14/04/2025)

## Wihtout loop

```bash
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
touch latihan1.txt
touch latihan2.txt
touch latihan3.txt
touch latihan4.txt
touch latihan5.txt
ls
rm latihan4.txt
mkdir latihan4.txt
rm latihan5.txt
mkdir latihan5.txt
ls
rmdir latihan4.txt
```

## With loop

```bash
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
for i in {1..5}; do touch latihan$i.txt; done
ls
rm latihan4.txt
mkdir latihan4.txt
rm latihan5.txt
mkdir latihan5.txt
ls
rmdir latihan4.txt

```
## Moving songs to their corresponding folders

```bash
mkdir Blackpink Evanescence "Linkin Park"
for songs in Blackpink Evanescence "Linkin Park"; do mv *"$songs"* "$songs"/;done
```
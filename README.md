# belajar-vite

1. Membuat project vite 
    - run "npm init"
        setelah berhasil di instal lalu buka project menggunakan IDEA , 
    - lalu tambahn "type":"module" di file package.json
2. Menginstal Vite Dependency
    - run "npm install --save-dev vite"
3. Menjalankan Aplikasi vite 
    - run "npx vite" . 
    - vite menggunakan file index.html sbg entry point .
    - untuk melihat opsi ketika menjalnkan vite , gunakan perintah "npx vite -- help"
4. Menjalankan TypeScript di Vite
    - run "npm install --save-dev typescript" untuk install dependency typescript
    - run "npx tsc --init" untuk setup TypeScript (tsconfig.json)
5. Build vite
    - untuk melakukan build , menggunakan perintah : npx vite build
    - untuk melihat opsi apa saja yg bisa di ubah , gunakan perintah : npx vite build --help
    - secara default hasil build akan disimpat di folder dist
6. Node Dependency 
    - install dependency UUID, run : npm install uuid
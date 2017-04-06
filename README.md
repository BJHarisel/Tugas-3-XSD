# Tugas-3-XSD
Boby Jamis Hari sel-1154040

**************
Analisis PesertaBimbel.xml :
Dalam kode tersebut ada tag <?xml version="1.0" encoding="UTF-8"?> itu merupakan tag penting atau 
jantungnya dari xml, merupakan sebuah Instruksi Proses / direktif khusus untuk mengelola  xml, Jadi 
jika kita ingin membuat sebuah xml  maka Perintah tersebut harus ada, jika tidak maka srcpt tersebut 
tidak bisa di compile menjadi xml. Diawali <?....?>

<Kursus Data="Peserta" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="Kursus.xsd">
adalah sebuah schema XSD, Dimana xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" sebagai pendeklarasi standar namespace, dan 
xsi:noNamespaceSchemaLocation="Kursus.xsd" adalah lokasi skema XML yaitu daro Kursus.xsd.

Dalam kode PesertaBimbel.xml  tersebut memiliki 1  element. Element sendiri merupakan nama teknis untuk 
tag yang berpasangan dimulai dari tag pembuka dan tag penutup pada dokumen XML. 
1 element/class dalam oop yang dimiliki kode tersebut adalah <Kursus>...</Kursus> dalam 
element tersebut mempunyai 10 Sub element yaitu <nama>..</nama>, <nip>..</nip>, 
<umur>..</umur>, <jeniskelamin>..</jeniskelamin>, <alamat>..</alamat>, 
<kelas>..</kelas>, <phone>..</phone>, <email>..</email>, <kampus>..</kampus>, 
<alamat>..</alamat>, dimana <alamat>..</alamat> adalah anak dari sub elemant <kampus>..</kampus>.
Didalam kode tersebut disematkan data-data atau entitaas yang akan dimunculkan. Jadi semua kode tersebut akan di compile.




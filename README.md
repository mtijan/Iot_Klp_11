# Iot_Klp_11

# swe-G2-iot-project
This is the repository for Group 2's IOT project for SWE course in UTM FKE. 

### Navigate this repo
The list below stacks the most recently created folder at the top
```
master
L IdleWasher_Flask_API_Server     - A folder for the code used in making the Flask web server for the project (Milestone 3)
L IdleWasher_ESP8266_LightSensor  - A folder for code used in the ESP8266 reading & sending data to server (Milestone 3)
L images        - A folder for storing the pics used in README.md files. 
L UML diagrams  - A folder for the UML models for the main project (Milestone 2.1)
L Test Flask Server - A test Flask Web app for suggesting a content (Milestone 1.3) 
L Test              - A Python script to test collaborating on Github (Milestone 1.2)
```


### Table of contents
1. [Main Project Details](#project)
    1. [Problem Statement](#prob)
    2. [Proposed solution](#sol)
    3. [Use Case diagram](#uc)
    4. [System architecture](#sysarc)
    5. [Hardware](#hw)
    6. [Communication Protocol](#comm)
    7. [Server & Hosting](#cloud)
    8. [Frontend](#ui)


<br/>

# Main Project: Idle Washer 🧺 <a name="project"></a>

### Problem Statement <a name="prob"></a>

>**tldr**: *Inconvenient for dorm residents to physically check if shared washing machine is available to use.*
```
Ketersediaan lahan parkir yang terbatas di lingkungan kampus menjadi tantangan utama bagi mahasiswa, staf, dan pengunjung.
Situasi ini menyebabkan ketidaknyamanan dan kesulitan saat mencari tempat parkir yang memadai, terutama pada jam-jam sibuk.
Mahasiswa dan staf sering kali harus meluangkan waktu lebih lama untuk menemukan tempat parkir yang tersedia, yang pada
gilirannya mengganggu jadwal perkuliahan, tugas, dan pekerjaan mereka. Bahkan, dalam beberapa kasus, hal ini menyebabkan
keterlambatan atau kehilangan sesi penting di dalam kelas atau pertemuan.

Selain itu, keterbatasan lahan parkir juga memunculkan perilaku parkir sembarangan yang tidak teratur dan tidak sesuai
dengan aturan. Kendaraan sering diparkir di tempat yang tidak diizinkan, menyebabkan kemacetan dan gangguan di area parkir.
Hal tentu saja menciptakan ketidaknyamanan bagi pengguna lainnya yang ingin memasuki atau meninggalkan area parkir.

Ketidakmampuan untuk menangani ketersediaan lahan parkir dengan efisien juga mengurangi penggunaan ruang yang seharusnya
bisa dioptimalkan untuk keperluan lain di kampus. Dengan demikian, masalah ini tidak hanya terkait dengan ketersediaan
parkir, tetapi juga dampaknya pada produktivitas, kenyamanan. Pengembangan sistem parkir pintar diharapkan dapat
mengatasi permasalahan ini dengan memanfaatkan teknologi untuk memantau dan mengelola ruang parkir secara efisien.
Dengan sistem ini, diharapkan bahwa mahasiswa, staf, dan pengunjung dapat dengan mudah menemukan tempat parkir yang tersedia,
memastikan parkir yang teratur sesuai dengan zona yang ditentukan, serta mengurangi kecenderungan perilaku parkir sembarangan.
Hal Ini akan meningkatkan pengalaman pengguna, meningkatkan efisiensi penggunaan lahan, dan menciptakan lingkungan kampus yang lebih aman dan teratur.

```

<br/>

### Our Solution <a name="sol"></a>
Solusi yang kami tawarkan berupas sebuah sistem IoT yang dapat mendeteksi kendaraan yang keluar masuk. Sistem ini akan menampilkan kendaraan yang masuk kedalam komplek universitas pertamina. Kendaraan yang masuk akan tercatat didalam sistem dan sistem secara otomatis akan mengurangi slot parkir yang tersedia. Hal tersebut dapat meminimalisir kepadatan di area parkir komplek universitas pertamina.

<br/>

### Use case diagram <a name="uc"></a>

![Use case diagram]()

**Tentative features**
- booking slots for using the washing machine

<br/>


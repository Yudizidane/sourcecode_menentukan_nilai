# sourcecode_menentukan_nilai
Memenuhi Tugas MataKuliah GUI

Microsoft Windows [Version 10.0.17134.648]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\User>python
Python 3.7.1 (default, Dec 10 2018, 22:54:23) [MSC v.1915 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> def Standar_Penilaian(nilai_mahasiswa):
...     if(nilai_mahasiswa<= 100 and nilai_mahasiswa >= 80):
...             print ("Nilai Mahasiswa A")
...     elif (nilai_mahasiswa <80 and nilai_mahasiswa >=70):
...             print ( "Nilai Mahasiswa B")
...     elif (nilai_mahasiswa <70 and nilai_mahasiswa >=60):
...             print ( "Nilai Mahasiswa C")
...     elif (nilai_mahasiswa <60 and nilai_mahasiswa >=40):
...             print ( "Nilai Mahasiswa D")
...     elif (nilai_mahasiswa <40 and nilai_mahasiswa >=0):
...             print ( "Nilai Mahasiswa E")
...     else:
...             print("Inputan Anda Salah")
...
>>> Standar_Penilaian(98)
Nilai Mahasiswa A
>>> Standar_Penilaian(75)
Nilai Mahasiswa B
>>> Standar_Penilaian(65)
Nilai Mahasiswa C
>>> Standar_Penilaian(51)
Nilai Mahasiswa D
>>> Standar_Penilaian(39)
Nilai Mahasiswa E
>>>

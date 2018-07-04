# Fundamental
Contoh Script Pyhthon FUNDAMENTAL


message = ('Hello World')
nama = ('Noor K Rachmanto')
usia = 3
lingkar_perut = 20,5

print(message)
print(nama)
print(usia)
print(lingkar_perut)

if usia <= 17:
    print('Jangan nonton film Dewasa')
    print('Masih Kecil')
else:
    print('Menuju Dewasa')

if lingkar_perut < 30:
    print('Kurus')
elif lingkar_perut < 40:
    print('Berisi')
else:
    print('Genduttttttt')

for i in range(2,3):
    print(message)

while usia > 0:
    print('Usia saat ini %s' % usia)
    print('Masih Hidup')
    usia = usia - 1

daftar_nama =['Rachman','To','Saekan','Fakih']
print(daftar_nama)
daftar_nama.append('Amas')
daftar_nama.append('Bangke')
print(daftar_nama)

for dn in daftar_nama:
    print('nama lain kamu adalah %s,padahal nama asli kamu itu %s' % (dn,nama))

manusia = {}
manusia['nama'] = 'Noor'
manusia['sex'] = 'Lalaki'
manusia['status'] = 'Pelajar'
print(manusia)
manusia['nama'] = 'Noor Kemal'
print(manusia)
manusia['alamat'] = 'Kasomalang'
print(manusia)

import json
print(json.dumps(manusia))

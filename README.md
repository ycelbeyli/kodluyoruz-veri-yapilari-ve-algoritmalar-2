# Kodluyoruz - Veri Yapıları ve Algoritmalar "Merge Sort Projesi"

### Soru 1: [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

#### Cevap 1 :
#### Birinci aşama: [16,21,11,8,12,22] dizinini iki gruba bölüyoruz.
#### İkinci aşama: [16,21,11] Birinci grup, [8,12,22] İkinci grup.
#### Üçüncü aşama: Birinci grubu parçalara ayırıyoruz. --> [16,21,11] --> [16,21], [11] --> [16], [21], [11] --> [16,21], [11] --> [11,16,21]
#### Dördüncü aşama: İkinci grubu parçalara ayırıyoruz. --> [8,12,22] --> [8,12], [22] --> [8], [12], [2] --> [8,12], [22] --> [8,12,22]
#### Beşinci aşama: İki grubu da sıralı bir şekilde birleştiriyoruz. --> [8,11,12,16,21,22]

### Soru 2: Big-O gösterimini yazınız.
#### Cevap 2: O(nlogn)


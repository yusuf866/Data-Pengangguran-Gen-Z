# Data-Pengangguran-Gen-Z
#Sebuah coding tentang data pengangguran Gen Z
import pandas as pd

# Membuat DataFrame dengan data pengangguran Gen Z
data = {
    'Usia': [15, 16, 17, 18, 19, 20, 21, 22, 23, 24],
    'Jumlah_Pengangguran': [3600000, 400000, 500000, 600000, 700000, 800000, 900000, 1000000, 1100000, 1200000],
    'Tingkat_Pengangguran': [9.37, 10.0, 10.5, 11.0, 11.5, 12.0, 12.5, 13.0, 13.5, 14.0]
}

df = pd.DataFrame(data)

# Menampilkan DataFrame
print("Data Pengangguran Gen Z:")
print(df)

# Analisis data
total_pengangguran = df['Jumlah_Pengangguran'].sum()
rata_tingkat_pengangguran = df['Tingkat_Pengangguran'].mean()

print("\nTotal Jumlah Pengangguran Gen Z:", total_pengangguran)
print("Rata-rata Tingkat Pengangguran Gen Z:", rata_tingkat_pengangguran)

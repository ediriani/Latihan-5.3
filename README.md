# Fungsi konversi Celcius ke Fahrenheit
celcius_ke_fahrenheit = lambda c: (9/5) * c + 32

# Fungsi konversi Celcius ke Reamur
celcius_ke_reamur = lambda c: 0.8 * c

# Test-case
print("Input C = 100. Output F =", celcius_ke_fahrenheit(100))
print("Input C = 80. Output R =", celcius_ke_reamur(80))
print("Input C = 0. Output F =", celcius_ke_fahrenheit(0))

    sleep(0.200)
    print(dau,f'\033[1;32m🌸 Đang Delay Reg Pro5 LÝ VĂN VƯƠNG > {ti} < Giây  ',end='\r')
    sleep(0.200)
    print(dau,f'\033[1;31m🌸 Đang Delay Reg Pro5 LÝ VĂN VƯƠNG > {ti} < Giây  ',end='\r')
    sleep(0.200)
    print(dau,f'\033[1;31m🌸 Đang Delay Reg Pro5 LÝ VĂN VƯƠNG > {ti} < Giây  ',end='\r')
    sleep(0.200)
    print(dau,f'\033[1;36m🌸 Đang Delay Reg Pro5 LÝ VĂN VƯƠNG > {ti} < Giây  ',end='\r')
    sleep(0.200)
cookies = (ck)#cookies acc cần reg (chỉ acc đang reg được pro5 mới dùng được):
while True:
    arrayho = ["Nguyễn", "Trần", "Lê", "Phạm", "Hoàng", "Huỳnh", "Võ", "Vũ", "Phan", "Trương", "Bùi", "Đặng", "Đỗ", "Ngô", "Hồ", "Dương", "Đinh"]
    arraylot = ["Công", "Đức", "Duy", "Gia", "Anh", "Hồng", "Đinh", "Quốc", "Quỳnh","Vĩnh"]
    arrayten = ["Hưng","Anh", "Văn", "Tuấn", "Hoàng", "Quốc", "Năm", "Giang", "Khang", "Dương", "Phúc", "Thiên", "Hùng", "Kiệt", "Châu", "Quỳnh", "huệ", "Tuấn", "Khánh", "Trân", "Yên", "Lợi", "Danh", "Vinh", "Nhi", "Nhí", "Quốc", "Anh", "Danh", "Hân", "Giang","Phán"]
    ho = random.choice(arrayho)
    lot = random.choice(arraylot)
    ten = random.choice(arrayten)
    name = str(ho+' '+lot+' '+ten)
    dem = dem+1
    print(dau,dem,reg_pro5(cookies, name).Reg())#kết quả trả về của api
    delay(dl);

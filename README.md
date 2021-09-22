# vietnam_phone_regex
Regex for Viet Nam phone number, include cellphone and telephone | Regex Số điện thoại Việt Nam, bao gồm cả số điện thoại bàn

# Viet Nam Phone Number Regex. This regex include:
- Cellphone number: Viettel, Vinaphone, Mobiphone, Vietnamobile, Iteltelecom, Reddi (055)
- Telephone number (such as: 024, 028,...)
- Start with ```0``` or ```84```
- Exactly 10 or 11 numbers

---

# Regex số điện thoại Việt Nam, bao gồm:
- Số điện thoại di động
- Số điện thoại bàn
- Bắt đầu bằng ```0``` hoặc ```84```
- Có chính xác 10 hoặc 11 ký tự (nếu đầu số máy bàn & bắt đầu bằng 84 thì sẽ có 12 ký tự)

---

Regex = ```^(0|84)(2(0[3-9]|1[0-6|8|9]|2[0-2|5-9]|3[2-9]|4[0-9]|5[1|2|4-9]|6[0-3|9]|7[0-7]|8[0-9]|9[0-4|6|7|9])|3[2-9]|5[5|6|8|9]|7[0|6-9]|8[0-6|8|9]|9[0-4|6-9])([0-9]{7})$```

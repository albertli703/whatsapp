# whatsapp

This is a python code to convert exported Whatsapp Chat txt file to xlsx file to enable message filtering.

Choose txt_to_xlsx for exported format dd/m/yyyy hh:mm - Sender: Message
Choose txt_to_xlsx_chinese for exported format [dd/m/yyyy 上午 h/mm/ss] Sender: Content

The code splited each line of the txt file into 4 parts:

1. Date
2. Time
3. Sender
4. Content

If datetime or sender information is not presented, it is classified as continued message from the previous sender/line.

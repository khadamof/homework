# # №1
# davlatlar = {
#     'uzbekistan':{
#         'poytaxti':'Toshkent',
#         'hududi':448978,
#         'aholisi':33000000,
#         'pul birligi':'so\'m'
#     },
#     'Rossiya': {
#         'poytaxti': 'Moskva',
#         'hududi': '17.125.191 km',
#         'aholisi': '146.203.613mln',
#         'pul birligi': 'rubl'
#     },
#     'AQSH': {
#         'poytaxti': 'Berlin',
#         'hududi': 9522055,
#         'aholisi': 341000000,
#         'pul birligi': 'EUR'
#     },
#     'portugaliya': {
#         'poytaxti': 'Lissabon',
#         'hududi': 92.3_000,
#         'aholisi': '10,53mln',
#         'pul birligi': 'EUR'
#     }
# }
# for i, info in davlatlar.items():
#     print(f"{i} ning poytaxti: {info['poytaxti']}\n"
#           f"hududi: {info['hududi']}\n"
#           f"aholisi soni: {info['aholisi']}\n"
#           f"pul birligi: {info['pul birligi']}\n")
#
# # №2
#
# asd = input("davlat nomini kiriting: ")
# if asd in davlatlar.keys():
#     qwe = davlatlar[asd]
#     print(f"{asd} ning poytaxti {qwe['poytaxti']}\n"
#           f"hududi {qwe['hududi']}\n"
#           f"aholisi {qwe['aholisi']}\n"
#           f"pul birligi {qwe['pul birligi']}")
# else:
#     print("kechirasiz bizda bu davlat haqida malumot yo'q")

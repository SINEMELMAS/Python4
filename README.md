# Python4
4th look for Python
seconds=int(input('Enter a seconds. '))
if seconds>=3600:
   hours=seconds/3600
   minutes_2=(seconds%3600)/60
   new_seconds=(seconds%3600)%60
   print('It is', f'{hours: .0f}','hours', f'{minutes_2: .0f}','minutes', f'{new_seconds: .0f}','second')

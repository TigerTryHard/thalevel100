# print('\n'.join(
    [''.join(
        [('Tha'[(x - y) % 3]  # Modulo 3 instead of 8
          if ((x * 0.05) ** 2 + (y * 0.1) ** 2 - 1) ** 3 - (x * 0.05) ** 2 * (y * 0.1) ** 3 <= 0
          else ' ')
         for x in range(-30, 30)])
     for y in range(15, -15, -1)]
))

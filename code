import random
import string

def pass_generator(length):
  if length <=0:
    return "Tamanho deve ser maior que 0"

  #
  letter_upper = string.ascii_uppercase
  letter_minus = string.ascii_lowercase
  num = string.digits
  espec = string.punctuation
  #
  sum = letter_upper + letter_minus + num + espec
  #
  password = ''.join(random.choice(sum) for _ in range(length))
  return password

length = int(input("Insira o tamanho da senha: "))
generated_password = pass_generator(length)
print(f"sua senha gerada é: {generated_password}")

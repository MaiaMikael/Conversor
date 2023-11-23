# Conversor
def converter_quilos_para_toneladas(quilos):
  """Converte quilos para toneladas.

  Args:
    quilos: A quantidade de quilos a ser convertida.

  Returns:
    A quantidade de toneladas equivalente.
  """

  toneladas = quilos / 1000

  return toneladas


if __name__ == "__main__":
  quilos = float(input("Quantos quilos você deseja converter? "))

  toneladas = converter_quilos_para_toneladas(quilos)

  print(f"{quilos} quilos equivalem a {toneladas:.2f} toneladas.")

print("escolha uma palavra para ser traduzida:\n1-Gato\n2-Cachorro\n3-Computador\n4-Dor\n"
      "5-Cinco\n6-Seis\n7-Sete\n8-Oito\n9-Nove\n10-Dez")
while True:
    escolha=input("Qual palavra traduzir?: ").strip().lower()
    idioma=input("Digite Em Qual Lingua?\n1-Ingles\n2-Alemão\n3-Espanhol\n:")
    match escolha:
        case 'gato':
            match idioma:
                case '1':
                    print("Cat")
                case '2':
                    print('Katze')
                case '3':
                    print('Gato')
        case 'cachorro':
            match idioma:
                case '1':
                    print("Dog")
                case '2':
                    print('Welpe')
                case '3':
                    print('Perro')
        case 'computador':
            match idioma:
                case '1':
                    print("Computer")
                case '2':
                    print('Computer')
                case '3':
                    print('computadora')
        case 'dor':
            match idioma:
                case '1':
                    print("Pain")
                case '2':
                    print('Schmerz')
                case '3':
                    print('dolor')
        case 'cinco':
            match idioma:
                case '1':
                    print("Five")
                case '2':
                    print('fünf')
                case '3':
                    print('Cinco')
        case 'seis':
            match idioma:
                case '1':
                    print("Six")
                case '2':
                    print('sechs')
                case '3':
                    print('seis')
        case 'sete':
            match idioma:
                case '1':
                    print("Cat")
                case '2':
                    print('Katze')
                case '3':
                    print('Gato')
        case 'oito':
            match idioma:
                case '1':
                    print("Eigth")
                case '2':
                    print('acht')
                case '3':
                    print('ocho')
        case 'nove':
            match idioma:
                case '1':
                    print("nine")
                case '2':
                    print('neun')
                case '3':
                    print('nueve')
        case 'dez':
            match idioma:
                case '1':
                    print("Ten")
                case '2':
                    print('zehn')
                case '3':
                    print('Diez')
        case _:
            print("Palavra Não Encontrada")
    con=input("Continuar")
    match con:
        case  's':
            continue
        case _:
            break

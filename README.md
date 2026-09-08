#standBY im working on this program ;)


#prepware

question_count = 76

while True:
    cmd = input("> ").strip().lower()
    if cmd == 'questions':
        print(f'yeah its {question_count} questions')

    elif  cmd == 'exit': 
         break
    else:
             print("Unknown command")

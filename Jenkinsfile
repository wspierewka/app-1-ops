// Sprawdzenie, czy podano dokładnie dwa argumenty
if (args.length != 2) {
    println "Podaj dokładnie dwie liczby jako argumenty."
    System.exit(1)
}

try {
    // Przekształcenie argumentów na liczby typu Double
    double liczba1 = args[0].toDouble()
    double liczba2 = args[1].toDouble()

    // Obliczenie średniej
    double srednia = (liczba1 + liczba2) / 2

    println "Średnia podanych liczb to: $srednia"
} catch (NumberFormatException e) {
    println "Podano nieprawidłowe dane. Upewnij się, że oba argumenty są liczbami."
}

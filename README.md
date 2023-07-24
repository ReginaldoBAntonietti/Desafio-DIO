# desafio1-dio

// Desafio 1: Fundamentos de Swift e iOS
// Desenvolvedor: Reginaldo B. Antonietti
// Exercício feito em: 24/07/2023

let vNome1: String = "Steve"
var vNome2: String? = "Jobs"

print("Variável constante vNome1: \(vNome1)")
print("Variável opcional  vNome2: \(vNome2!)")
print("\n")


// OPCIONAL BINDING
if let vNomeComplementar = vNome2 {
    
    print("Interpolação da constante e variável opcional: \(vNome1) \(vNomeComplementar) \n")
    print()
    
}


// OPCIONAL BINDING
vNome2 = "Wozniak"
print("Variável opcional vNome2 com novo valor default: \(vNome2!) \n\n")

if let vNomeComplementar = vNome2 {
    
    print("Nova interpolação da constante e da variável opcional: \(vNome1) \(vNomeComplementar) \n\n")
    print("Opcional Binding feito, variável OPCIONAL vNome2 desembrulhada e prints feitos de acordo com o que o exercício pede.")

}

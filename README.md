Mano pirmoji GIT repozitorija
Ši repozitorija skirta tam, kad išmokti naudotis projektų versijavimo kontrolės komandinės eilutės sąsaja - GIT CLI. Tam jums reikės parsisiųsti ir įsirašyti: https://git-scm.com/downloads

Repozitorijos parsiuntimas
Atsidarykite GIT CLI (GIT bash).
Naudodami komandą pakeiskite savo darbinę kategoriją į tą, kurioje norite parsiųsti repozitoriją
Parsiųskite repozitoriją: git clone https://github.com/ZilvinasVidmantas/test
Pakeiskite darbinę kategoriją į parsiųstos repozitorijos kategoriją cd test
Pagrindinės komandos
**1. git add** -> failų paruošimas patvirtinimui **...*git add* -> prideda failą nurodytu pavadinimu **git add** . -> Prideda visus pakitusius failus

**2. git diff** -> skirtumas tarp dviejų failų, ar dviejų to paties failo versijų git diff -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o

**3. git status** -> parodo pakitusių failų būseną

**4. git branch** -> komanda, kuri naudoja operacios su šakomis git branch -a -> parodo visas parsiųstas šakas ir šiuo metu aktyvią šaką

**5. git commit** -> komanda skirta užtvirti projekto pakitimui git commit -m "Žinutė apibūdinanti pakitimą"

**6. git push** -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką
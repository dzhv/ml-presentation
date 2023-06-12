# Things to mention

suprast geriau CrossEntropy loss, užsirašyt, pagalvot kaip aiškinsiu

paminėt, kad MLP yra blogas pasirinkimas (palygint gale su CNN?)

kodėl blogai trainint tik ant train?
    kodėl reikia val?
    kodėl reikia test?

kodėl, jei iš naujo traininu, tai lossas iškart gan žemas?
    nes modelis jau "išmokęs" kažką



# Scope

- MNIST problem and why we need ML

- Defining ML model as a mathematical function
  - explaining how an image fits to function params
  - weights?
  - Model code

- Training
  - what does it mean?
    - passing examples of data and adjusting function weights each time
    - example with a simple function: f(x) = kx^2 + c
    - simple training code

- Explaining Back Propogation
  - loss function
  - derivatives
  - ball rolling into a valley analogy

- Train - val - test
  - graphs showing train and val stats

- <Training runs>

- Trying out on test set
  - looking at failed attempts and pondering


# Išvestinė

    išvestinė iš esmės pasako "funkcijos kitimo greitį" / "rate of change for the function" kažkuriam taške,
    bet čia labai vague
    tiksliau būtų sakyt, kad išvestinė parodo, ar funkcijos reikšmė didėja ar mažėja ir kaip greitai, jei minimaliai padidini inputą (pagal kurį skaičiavai išvestinę)

# mayrton

class Usuario {
    #nome = "";
    #login = "";
    #senha = "";
    constructor(nome, login, senha) {
        this.#nome = nome;
        this.#login = login;
        this.#senha = senha;
    }
    get nome() {
        return this.#nome;
    }
    set nome(nome) {
        this.#nome = nome;
    }
    get login() {
        return this.#login;
    }
    set login(login) {
        return this.#login;
    }
    get senha() {
        return this.#senha;
    }
    set login(senha) {
        return this.#senha;
    }
}
 
function cadastrarUsuario() {
    let vetor = []
    let nome  = ""
    let login = ""
    let senha = ""
    for (let i = 0; 1<3; ++i) {
        nome = prompt("Digite seu nome");
        login = prompt("Digite seu login");
        senha = prompt("Digite sua senha");
        vetor.push(new Usuario(nome, login, senha));
        }
        for(let i = 0; 1<3; ++i) {
            console.log("Nome:"  + vetor[i].nome);
            console.log("Login:" + vetor[i].login);
            console.log("Senha:" + vetor[i].senha);
}
}
cadastrarUsuario();

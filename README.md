.contato {
    background-color: var(--branco);
    padding: 1em;
}

.contato__titulo,
.contato__texto {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.contato__titulo {
    font-size: 18px;
    font-weight: 500;
}

.contato__texto {
    font-weight: 300;
    margin: 1em 0;
}

.contato__email {
    padding: 1em;
    border: 1px solid var(--azul);
    border-radius: 24px;
    width: 90%;
    color: var(--azul);
}

.contato__email::placeholder {
    font-family: var(--fonte-principal);
    color: var(--azul);
    background: url("../img/Email.svg") no-repeat 5%;
    padding-left: 2em;
}

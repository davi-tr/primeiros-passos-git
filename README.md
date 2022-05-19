<div style="display: inline_block">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width = 50/> 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width = 50/> 
</div>

# Como fazer um commit

## Passo a passo de como realizar um commit

### Antes de tudo usaremos os comando abaixo para configurar nossas credenciais pela primeira vez.

### Neste você deve informar seu nome de usuário igual ao do github.

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled.png)

### Neste você deve informar seu e-mail, o mesmo do github.

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%201.png)

### Agora podemos iniciar, sempre utilize o comando >***git status***, ele irá informar o estado atual do seu repositório local

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%202.png)

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%203.png)

### Caso haja alguma alteração será listado na resposta do comando, como mostrado abaixo

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%204.png)

### Após isso, podemos dar inicio ao procedimento, devemos usar o comando >***git add .*** para que possamos adicionar todas as alterações para staged

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%205.png)

### agora podemos realizar o comando >***git commit -m “comentario que será postado junto ao commit”***

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%206.png)

### Desta para que o upload seja realizado com sucesso devemos usar o comando >***git push origin main***

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%207.png)

### Pronto, com isso concluímos nosso commit. Se usarmos o comando ***>git status***, veremos que o commit foi executado com sucesso.

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%208.png)

### É importante ter em mente que deve ser feito o uso do comando.
#### ***git config --global credential.helper store***
### Dessa forma manteremos as credencias de login salvas no terminal, facilitando assim novos commits.

![Untitled](Como%20fazer%20um%20commit%2095f11de9ef7c440fb795295ee9908a26/Untitled%209.png)
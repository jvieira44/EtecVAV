# 1 - Definição de CSS

* __CSS__ é uma linguagem usada para estilizar páginas web. Ele trabalha em conjunto com o __HTML__ para definir como os elementos serão mostrados na tela, assim deixando as informações organizadas em diferentes dispositivos e tamanhos de tela, sem que a organização da página mude.

## O que o CSS pode fazer?

* Alterar cores de texto e fundo;
* Definir tamanhos e tipos de fonte;
* adicionar animações e efeitos visuais;
* criar layouts que se adaptam ao dispositivo.

# 2 - Formato do CSS

O CSS é escrito usando:
- seletor
- propriedade
- valor

Exemplo:

```css
p {
  color: blue;
  font-size: 20px;
}
```
Nesse exemplo:

* p é o seletor
* color e font-size são propriedades
* blue e 20px são os valores
  
# 3 - Tipos de CSS

## ⚙️ IN-LINE:

* CSS in-line é quando o estilo é aplicado diretamente dentro da própria tag HTML, usando o atributo `style` ou seja cada elemento recebe sua própria aparência separada. Esse tipo de CSS é simples de usar e funciona rapidamente mas, não é muito organizado, porque se mistura com HTML. Além disso, você precisa repetir o mesmo código várias vezes (e não usar uma vez só para todos elementos) isso dificulta a manutenção principalmente se o código for grande, já que você precisa editar elemento por elemento.

<br>
  
![gif1](https://github.com/etecvav26-c1b-06/portfolio-pw1/blob/main/2-bim/pesquisa.md/internal.gif?raw=true)

## 📁 IN-FOLDER:

* CSS in-folder (mais conhecido como CSS externo) é quando os estilos são escritos em um arquivo `.css` que ficam geralmente dentro de uma pasta e depois são conectados ao HTML. Nesse caso, o HTML cuida apenas da estrutura da página, já o CSS controla a aparência. Essa forma é mais organizada, permite usar os mesmos códigos em várias páginas e facilita muito a manutenção e edição do código. Por isso, é a maneira mais recomendada de usar CSS em projetos reais.

<br>

![gif2](https://github.com/etecvav26-c1b-06/portfolio-pw1/blob/main/2-bim/pesquisa.md/gif2julio.gif?raw=true)

  
## 🔗 EXTERNAL

* CSS External é uma forma de aplicar estilos a um site utilizando arquivos separados do HTML, ao invés de colocar o estilo dentro da própria pagina, cria-se um arquivo com extensão .CSS : __(Por exemplo: Styles.CSS)__. já no arquivo styles.css, você escreve o estilo:

<br>

![print1](https://github.com/etecvav26-c1b-06/portfolio-pw1/blob/main/2-bim/pesquisa.md/CSS%20External.png?raw=true)

<br>

* No HTML, usa-se a tag link dentro do head por exemplo:

<br>

![print2](https://github.com/etecvav26-c1b-06/portfolio-pw1/blob/main/2-bim/pesquisa.md/CSS2.png?raw=true)

<br>

### Simplificando ele é util porque:
* separa conteúdo (HTML) de aparência (CSS)
* um único arquivo CSS pode ser usado em várias páginas
* mudar um arquivo altera todo o site
* o navegador pode salvar o CSS na memória cache


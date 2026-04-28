# Macros úteis para o trabalho de design de material esportivo
## Carregar macros no corel
<img width="598" height="389" alt="image" src="https://github.com/user-attachments/assets/9bb29970-fe86-4bc6-bfdc-e1512fbbda4c" />
<img width="292" height="301" alt="image" src="https://github.com/user-attachments/assets/aab51888-691c-42b6-ac36-366c96b23093" />
<img width="1069" height="547" alt="image" src="https://github.com/user-attachments/assets/c14d2125-7ddf-487a-8923-7125a2839a77" />
<br>
<br>

* Gerador de Mosaicov3.gms: Permite gerar mosaicos de impresão a partir de uma frente e uma costa.
* InserirNome.gms: Permite selecionar um grupo de camisas e inserir vários nomes em lote, evitando digitação manual.
* InserirNumero.gms: Permite selecionar um grupo de camisas e inserir vários números em lote, evitando digitação manual.
* AjustarPagina.gms: Ajusta a pagina para os objetos existentes.

## Gerador de mosaico para impressão

### Selecionar frente e costa
Antes de executar a macro é necessário selecionar a frente e costa do material esportivo desejado, exemplo:
<img width="515" height="453" alt="image" src="https://github.com/user-attachments/assets/df344dc9-28b7-41ca-9d66-247c30f82e1c" />


A frente é um grupo de objeto e as costas é outro grupo de objetos, repare que ao selecinar a quantidade de objetos selecionados é 2.
Com base nesses 2 objetos(frente e costa) a macro consegue gerar a quantidade de camisas que você precisa já organizadas para impressão.

<br>
<br>

### Executar macro
<img width="911" height="166" alt="image" src="https://github.com/user-attachments/assets/f3bb654f-2887-4cae-ba1a-45eedc5f763d" />
Ao clicar em start um formulário vai aparecer pedindo a largura da página de impressão e a quantidade de camisas a ser gerada, basta informar e clicar em gerar.
<img width="734" height="578" alt="image" src="https://github.com/user-attachments/assets/c20c33c1-88a2-4811-ab92-72aa825f6b7c" />

<br>
<br>

## Inserir nomes em lote
Uma vez gerado o mozaico, basta selecionar todas as camisas geradas e executar a macro de nomes
<img width="1179" height="588" alt="image" src="https://github.com/user-attachments/assets/2ed7612a-325f-4877-851e-c84fe7187cf1" />

Copie sua lista de nomes da planilha e cole  no formulário que se abriu. A macro vai buscar a referência(Nome) e trocar cada uma por cada item que você informou na lista. Repare que temos 3 Referencias (Nome) nos objetos selecionados e estamos informando 3 nomes na lista, a quantidade precisa ser igual.
<img width="256" height="115" alt="image" src="https://github.com/user-attachments/assets/dfa53d8c-89dc-482f-8e04-ed2819773cc7" />
<img width="765" height="739" alt="image" src="https://github.com/user-attachments/assets/e2698ca1-adf3-4eb4-a827-1a60831f093d" />

<br>
<br>

## Inserir números em lote
Similar ao passo de inserir nomes em lote, mas será utilizada outra macro
<img width="1407" height="727" alt="image" src="https://github.com/user-attachments/assets/6f06ee68-de3f-4e44-bac0-0caa2a6abdda" />

<br>
<br>

## Resultado final:
<img width="876" height="751" alt="image" src="https://github.com/user-attachments/assets/24821f1a-f7b7-4ea9-bd15-951199406d41" />

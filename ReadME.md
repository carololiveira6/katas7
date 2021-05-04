<em>20 - Entrega: Katas de JavaScript 7</em>

<h1>Katas de JavasScript 7 - Callbacks</h1>

Nesta entrega, você irá exercitar a criação e o uso das funções callback, e irá se familiarizar com o modo no qual os métodos incorporados do JavaScript funcionam nos bastidores.

O JavaScript fornece vários "métodos de iteração" baseados no mesmo tipo de padrão de callback que você viu no caso do forEach() na aula sobre Funções Callback. Essencialmente, eles são loops prontos, com alguns comportamentos adicionados para ter um pouco de variação do padrão.

<h2>Sua Tarefa</h2>

Sua tarefa será reproduzir o comportamento desses métodos de Array com suas funções callback, incluindo os parametros opcionais e sem usar as versões incorporadas do JavaScript:

<ol>
<li>

[forEach()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
</li>
<li>

[map()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
</li>
<li>

[some()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/some)
</li>
<li>

[find()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/find)
</li>
<li>

[findIndex()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex)
</li>
<li>

[every()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/every)
</li>
<li>

[filter()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/filtro)
</li>
</ol>

Dê os seguintes nomes a cada uma das funções: newForEach, newMap, newSome, newFind, newFindIndex, newEvery, newFilter. Sua implementação de cada um dos métodos de iteração acima deve resultar nos <em>mesmos argumentos e valores de retorno</em>.

IMPORTANTE: Para propósitos de teste/avaliação, é importante que você dê o nome do repositório de 'katas7', e que o nome das funções seja igual ao padrão mencionado acima.

<h2>Bônus</h2>

Implemente também sua própria versão dos seguintes métodos de array. Dê o nome das funções de acordo com o mesmo formato que você usou nos primeiros 7 métodos. A maioria deles não precisa de uma função callback. Você não precisa implementá-los em ordem:

<ul>
<li>

[concat()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)
</li>
<li>

[includes()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/contains)
</li>
<li>

[indexOf()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)
</li>
<li>

[join()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/join)
</li>
<li>

[slice()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)
</li>
<li>

[flat()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/flat)
</li>
<li>

[flatMap()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)
</li>
<li>

[Array.of()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/of)
</li>
</ul>

<h1>Envio</h1>

Faça o push do código para seu repositório no GitLab e use a função do GitLab Pages que permite que o site seja visualizado diretamente. No GitLab, por favor, adicione ka-br-<sua-turma>-correcoes como membro do seu projeto com a permissão "Reporter", e <strong>envie a url do seu gitlab pages (Ex: https://nomedeusuario.gitlab.io/katas7)</strong>.
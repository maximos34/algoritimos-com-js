//////////////////////////////////////////////////////////////////////////////
                             . OPERADORES
/////////////////////////////////////////////////////////////////////////////

                  . OPERADORES BINARIOS
      {
                  O javaScript possui tanto operadores bináros quanto unários
            e um operador ternário, o opeador condicional . Um operador
            binário exige dois operandos , um antes do operador e outro
            depois :

                  ( operando1 operador operando2 )

            Por exemplo , 3+4 ou x\*y.
      }

//////////////////////////////////////////////////////////////////////////////////

                . OPERADORES UNARIOS{
                  {Um operador unário exige um unico operando , seja antes ou depois do operador

                        ( operador operando )
                                 ou
                        ( operador operando )
                  Por exemplo , x++ ou ++x }
                  { Outro operador unario é o delete operando
                   O operador delete apaga um objeto , uma propiedade de um objeto ou um elemento no indice especifico de uma matriz .
                   A sintaxe é :
                   (delete nomeObjeto;
                    delete nomeObjeto.propriedade;
                    delete nomeObjeto[indice];
                    delete propriedade; // válido apenas dentro de uma declaração with)
                    onde nomeObjeto é o nome de um objeto, propriedade é uma propriedade existente e indice é um inteiro que representa a localização de um elemento em uma matriz.
                    A quarta forma é permitida somente dentro de uma declaração with para apagar uma propriedade de um objeto.
                    Você pode utilizar o operador delete para apagar variáveis declaradas implicitamente mas não aquelas declaradas com var.
                    Se o operador delete for bem-sucedido, ele define a propriedade ou elemento para undefined. O operador delete retorna verdadeiro se a operação for possível; ele retorna falso se a operação não for possível.
                    (
                        x = 42;
                        var y = 43;
                        meuobj = new Number();
                        meuobj.h = 4;    // cria a propriedade h
                        delete x;        // retorna true (pode apagar se declarado implicitamente)
                        delete y;        // retorna false (não pode apagar se declarado com var)
                        delete Math.PI;  // retorna false (não pode apagar propriedades predefinidas)
                        delete meuobj.h; // retorna true (pode apagar propriedades definidas pelo usuário)
                        delete meuobj;   // retorna true (pode apagar se declarado implicitamente)
                    )
                  }
                     }

////////////////////////////////////////////////////////////////////////////////////

                   . OPERADORES TERNARIOS{

                  O operador condicional é o unico operador JavaScript que utiliza três operandos .
                  O operador pode ter um de dois valores baseados em uma condição .
                  A sintaxe é

                  ( condicao? valor1 : valor2)

                  se "condição" for verdadeira , o operador terá o valor de valor1.
                  caso contrario , terá o valor de valor2 .
                  Você pode atualizar o operador condicional em qualquer lugar onde utilizaria um operdor padrão .

                  let status = ( idade>= 18 ) ? "adulto" : "menor de  idade"
                  
                  essa declaração atribui o valor "adulto" à variável 'status' caso
                  'idade' seja dezoito ou mais . caso contrário , atribui o valor 'menor de idade'
                   }

////////////////////////////////////////////////////////////////////////////////////

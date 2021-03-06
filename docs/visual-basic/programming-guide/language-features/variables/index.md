---
title: "Variáveis no Visual Basic"
ms.custom: 
ms.date: 2015-07-20
ms.prod: .net
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-visual-basic
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- VB
helpviewer_keywords:
- variables [Visual Basic]
- values [Visual Basic], storing
ms.assetid: 4cfaa06d-4ae3-4307-897b-cf599dc24caa
caps.latest.revision: 27
author: dotnet-bot
ms.author: dotnetcontent
translation.priority.ht:
- cs-cz
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- pl-pl
- pt-br
- ru-ru
- tr-tr
- zh-cn
- zh-tw
ms.translationtype: HT
ms.sourcegitcommit: 306c608dc7f97594ef6f72ae0f5aaba596c936e1
ms.openlocfilehash: 2fdc670bf4f17000809e75e32c32edb39abf0fed
ms.contentlocale: pt-br
ms.lasthandoff: 07/28/2017

---
# <a name="variables-in-visual-basic"></a>Variáveis no Visual Basic
Você normalmente precisa armazenar valores ao executar cálculos com o [!INCLUDE[vbprvb](~/includes/vbprvb-md.md)]. Por exemplo, talvez você queira calcular vários valores, compará-los e executar operações diferentes dependendo do resultado da comparação. Você precisará reter os valores se desejar compará-los.  
  
## <a name="usage"></a>Uso  
 O [!INCLUDE[vbprvb](~/includes/vbprvb-md.md)], assim como a maioria das linguagens de programação, usa variáveis para armazenar valores. Uma *variável* tem um nome (a palavra que você usa para se referir ao valor que a variável contém). Uma variável também tem um tipo de dados (que determina o tipo de dados que a variável pode armazenar). Se precisar armazenar um conjunto indexado de itens de dados estritamente relacionados, uma variável poderá representar uma matriz.  
  
 A inferência de tipo de variável local permite que você declare variáveis sem especificar de maneira explícita um tipo de dados. Em vez disso, o compilador infere o tipo da variável com base no tipo da expressão de inicialização. Para obter mais informações, consulte [Inferência de tipo de variável local](../../../../visual-basic/programming-guide/language-features/variables/local-type-inference.md) e [Instrução Option Infer](../../../../visual-basic/language-reference/statements/option-infer-statement.md).  
  
## <a name="assigning-values"></a>Atribuindo valores  
 Você pode usar instruções de atribuição para executar cálculos e atribuir o resultado a uma variável, conforme mostra o exemplo a seguir.  
  
 [!code-vb[VbVbalrVariables#1](../../../../visual-basic/programming-guide/language-features/variables/codesnippet/VisualBasic/index_1.vb)]  
  
> [!NOTE]
>  O sinal de igual (`=`) no exemplo é um operador de atribuição e não um operador de igualdade. O valor é atribuído à variável `applesSold`.  
  
 Para obter mais informações, consulte [Como inserir e remover dados de uma variável](../../../../visual-basic/programming-guide/language-features/variables/how-to-move-data-into-and-out-of-a-variable.md).  
  
## <a name="variables-and-properties"></a>Variáveis e propriedades  
 Como uma variável, uma *propriedade* representa um valor que você pode acessar. No entanto, ela é mais complexa que uma variável. Uma propriedade usa blocos de código que controlam como definir e recuperar seu valor. Para obter mais informações, consulte [Diferenças entre propriedades e variáveis no Visual Basic](../../../../visual-basic/programming-guide/language-features/procedures/differences-between-properties-and-variables.md).  
  
## <a name="see-also"></a>Consulte também  
 [Declaração de variável](../../../../visual-basic/programming-guide/language-features/variables/variable-declaration.md)   
 [Variáveis de objeto](../../../../visual-basic/programming-guide/language-features/variables/object-variables.md)   
 [Solução de problemas de variáveis](../../../../visual-basic/programming-guide/language-features/variables/troubleshooting-variables.md)   
 [Como inserir e remover dados de uma variável](../../../../visual-basic/programming-guide/language-features/variables/how-to-move-data-into-and-out-of-a-variable.md)   
 [Diferenças entre propriedades e variáveis no Visual Basic](../../../../visual-basic/programming-guide/language-features/procedures/differences-between-properties-and-variables.md)   
 [Inferência de Tipo de Variável Local](../../../../visual-basic/programming-guide/language-features/variables/local-type-inference.md)


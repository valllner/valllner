![image](https://github.com/valllner/valllner/assets/92387322/0ce9c12f-0e74-4688-8c4b-b3815d449b59)![image](https://github.com/valllner/valllner/assets/92387322/65108816-0de5-4648-97e9-26bef426e6ca)### Hi there 👋

![Alt-текст](https://images.unsplash.com/photo-1504805572947-34fad45aed93?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

#### Русакова Валерия
[Мои работы](https://legendary-baklava-3861d3.netlify.app)

## Контактная информация 👯
- **Email:** valeria_rskv04@mail.com
- **Телефон:** +375 33 677 33 55

## <img src="./EVT_NEW/lr10/assets/icons8-about-me-50.png" width="50"/> Обо мне
Я _мотивированный_ и _целеустремленный_ разработчик программного обеспечения с опытом работы в различных проектах. Мои сильные стороны включают _умение быстро обучаться_ новым технологиям, _аналитическое мышление_ и _командную работу_. Я стремлюсь к _постоянному развитию своих навыков_ и _поиску новых вызовов_.

## Образование 🔭

| Образование/курсы | Продолжительность |
| ----------- | ----------- | 
| БГУИР | 2021-2025 |
| Айти практикум | 2022-2023 |

## Владение английским языком 💬
- Английский на уровне среднего разговорного владения
- Хорошие навыки чтения и письма на английском
- Уверенное понимание иностранной речи в повседневных ситуациях

## Навыки 💬
- Языки программирования: Java, JavaScript
- Платформы: Windows
- Системы контроля версий: Git
- Инструменты разработки: IntelliJ IDEA, Visual Studio Code

<div id="langugages">
    <img src="./EVT_NEW/lr10/assets/908bcbe9a94d2bc69089a01a356d3a24.png" width="100px" alt="Java"/>
    <img src="./EVT_NEW/lr10/assets/orig.png" width="100px" alt="JavaScript"/>
    <img src="./EVT_NEW/lr10/assets/gas-kvas-com-p-logotip-maikrosoft-na-prozrachnom-fone-16.png" width="100px" alt="Micro"/>
     <img src="./EVT_NEW/lr10/assets/219-2192031_svg-studio-visual-visual-studio-code-logo-clipart.png" width="100px" alt="Code"/>
    <img src="./EVT_NEW/lr10/assets/IntelliJ-Idea-logo1.png" width="100px" alt="IntelliJ"/>
</div>

## Пример реализации интерполяционного поиска на Java
```java
public static int interpolationSearch(int[] integers, int elementToSearch) {

    int startIndex = 0;
    int lastIndex = (integers.length - 1);

    while ((startIndex <= lastIndex) && (elementToSearch >= integers[startIndex]) &&
           (elementToSearch <= integers[lastIndex])) {
        int pos = startIndex + (((lastIndex-startIndex) /
          (integers[lastIndex]-integers[startIndex]))*
                        (elementToSearch - integers[startIndex]));

        if (integers[pos] == elementToSearch)
            return pos;
        if (integers[pos] < elementToSearch)
            startIndex = pos + 1;
        else
            lastIndex = pos - 1;
    }
    return -1;
}


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

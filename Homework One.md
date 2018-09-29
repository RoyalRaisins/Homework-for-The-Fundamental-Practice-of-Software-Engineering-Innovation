# HomeWork One for The Fundamental Practice of Software engineering Innovation
>By CharlesW

People have developed many a set of tools to help simplify the building of webpages, and React as a a javascript library ranks among them.

Before learning the contents of this library I have no knowledge of other UI tool packs, so this is virtually a brand new realm of knowledge to explore to me. Also because of my insufficient knowledge in and lack of practice of Javascript and html, the report will mostly be what I've learned about React and comparison between what I already know about the basic functions of Javascript and what I've learned about the functions of React.

## Some features
- React uses render() to refresh the output on the webpage, and is only allowed to return one parameter.
- React uses prop and state to transist data between types, functions, and users. 
- React checks whether the value of state of the parameter given to render is alterd and changes the output if the value is shown.
- React simulates DOM so that we can interact with DOM much less.
- React has its own units and allows user-defined ones to be created.

## Comparisons and First-hand Experience
> Plainness
- When I first saw these codes in tutorial I was wondering if I entered the wrong page and was looking at HTML codes.
From my point of view, React uses a very direct and obvious way to modify the elements to be shown on the webpage. By obvious I refer to when another programmer is supposed to read the original code, the action would seem plain and simple.
- On the contrary, from my short experience in Javascript, html elements mostly don't show up in ordinary JS codes.


    ReactDOM.render(
     <div>
    <h1>菜鸟教程</h1>
    <h2>欢迎学习 React</h2>
    <p data-myattribute = "somevalue">这是一个很不错的 JavaScript 库!</p>
    </div>
    ,
    document.getElementById('example')
    );

>Elements as unit
- Another feature that is quite astonishing to me is the units（组件）in React. We can assemble many HTML elements to form a single unit, and with its methods efficiently manage these elements especially when they are logically connected.
- While in past the class I've learn about in HTML is about the colors and fonts in a div or header.


    function HelloMessage(props) {
    return <h1>Hello World!</h1>;
    }
 
    const element = <HelloMessage />;
 
    ReactDOM.render(
        element,
     document.getElementById('example')
    );

However, as a library capable of handling many difficult situations many satiating many different demands, React is much more than I already know about it, so my current understanding of it can be incorrect and is definitely not thorough.
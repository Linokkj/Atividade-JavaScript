function App(){
let a = Number (prompt("num 1"));
let b = Number (prompt("num 2"));

let mais = a+b;
let menos = a-b;
let vezes = a*b;
let dividir = a/b;

  return (
    <div>
      <p>
        <ul>
          <p>Soma:{mais}</p>
          <p>Subtração: {menos}</p>
          <p>Multiplicaçao: {vezes}</p>
          <p>Divisao: {dividir}</p>
        </ul>
      </p>
    </div>
  )

}

export default App

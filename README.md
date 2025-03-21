import React from 'react';

const FlowersLoveDemo = () => {
  // Estilos definidos en el CSS
  const flowerStyle = {
    backgroundColor: '#fae2bf',
    color: '#000',
    border: 'none',
    padding: '12px 20px',
    fontSize: '18px',
    fontFamily: 'cursive', // Usando cursive como alternativa a 'Flower'
    borderRadius: '10px',
    display: 'inline-block',
    margin: '20px'
  };

  return (
    <div className="container">
      <h2 className="mb-4">Demostración del estilo Flowers__Love</h2>
      
      <div style={flowerStyle}>
        Botón con estilo Flowers__Love
      </div>
      
      <div className="mt-8">
        <h3 className="mb-2">Código CSS:</h3>
        <pre className="bg-gray-100 p-4 rounded text-sm">
          {`.Flowers__Love {
    background-color: #fae2bf;
    color: #000;
    border: none;
    padding: 12px 20px;
    font-size: 18px;
    font-family: 'Flower';
    border-radius: 10px;
}`}
        </pre>
      </div>
    </div>
  );
};

export default FlowersLoveDemo;

class Fruits extends React.Component {
  constructor(props) {
    super(props);
  }
  render() {
    return (
      <div>
        <h2>Fruits:</h2>
        { <NonCitrus></NonCitrus> }

        { <Citrus></Citrus>  }
      </div>
    );
  }
};

class TypesOfFood extends React.Component {
  constructor(props) {
     super(props);
  }
  render() {
    return (
      <div>
        <h1>Types of Food:</h1>
        { <Fruits></Fruits> }

        { /* Change code above this line */ }
        <Vegetables />
      </div>
    );
  }
};

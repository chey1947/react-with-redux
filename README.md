##Steps of running this project

from the command prompt clone the project

* $git clone https://github.com/techsithgit/react-with-redux.git
* $cd react-with-redux
* $npm install
* $npm start

[Watch the Tutorial](https://youtu.be/Fq15pkckMqQ).

  const [isChecked, setIsChecked] = useState(Array(itemsFromBackend.length).fill(true));

  const handleCheckBox = (index) => {
    const newCheckedState = [...isChecked];
    newCheckedState[index] = !newCheckedState[index];
    setIsChecked(newCheckedState);
  };

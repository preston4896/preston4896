# Hi there, I am Preston Ong! 👋

<h2 align = "center" > Preston.sol </h2> 

```solidity
pragma soliditiy ^0.6.0;

contract Preston is Awesome {

  string profession;
  string currentLocation;
  string[] spokenLanguages;
  string[] codingLanguages;
  bool toTheMoon;
  
  function setProfile() public returns (string) {
    profession = "Blockchain Developer";
    currentLocation = "Malaysia";
    spokenLanguages = ["Mandarin Chinese", "English"];
    codingLanguages = ["Solidity", "C++", "Typescript", "Swift", "Python"];
    toTheMoon = true;
    
    return ("Nice to meet you!");
  }
  
}

```

![Preston's GitHub stats](https://github-readme-stats.vercel.app/api?username=preston4896&count_private=true&show_icons=true&theme=dark)

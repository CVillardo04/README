# js.NFT

// create a variable to hold your NFT's
const NFTs = []
// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT(_name,_age,_eyecolour,_heigth) {
  const NFT = {
    "name":_name,
    "age":_age,
    "eyecolour":_eyecolour,
    "heigth":_heigth
  }
NFTs.push(NFT);
console.log("Minted:"+_name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {
for(let i = 0; i < NFTs.length; i++){
  console.log("\nID:\t\t"+ (i + 1));
  console.log("\nName:\t\t"+ NFTs[i].name);
  console.log("Age:\t\t"+ NFTs[i].age); 
  console.log("Eyecolour:\t"+ NFTs[i].eyecolour);
  console.log("Heigth:\t"+ NFTs[i].heigth);
  
}
}
// print the total number of NFTs we have minted to the console
function getTotalSupply () {
 console.log("\n"+NFTs.length);
}

// call your functions below this line (dito na may iibahin)
mintNFT("Luffy", "22", "red", "5,7");
mintNFT("Zoro", "22", "green", "5,8");
mintNFT("Zanji", "23", "yellow", "5,8");
listNFTs();
getTotalSupply();


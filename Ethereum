pragma solidity 0.8.18;
contract MyToken {

    // public variables here
     string public tokenname="MINT";
     string public tokenabbrv="MNT";
     uint public totalsupply=0;
    // mapping variable here
      mapping(address=>uint)public total_balance;
    // mint function
      function mint(address i,uint value)public {
         totalsupply+=value;
         total_balance[i]+=value;
      }
    // burn function
      function burn(address b,uint _value)public {
        if(total_balance[b]>=_value){
         totalsupply-=_value;
         total_balance[b]-=_value;
      }
      }
}

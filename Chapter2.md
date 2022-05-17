Chapter 2 - Day 1

//Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. 
//Initialize it to "the best" when your contract gets deployed.

pub contract JacobTucker {
//
//State
//
pub let is: String

//
//Logic
//
  init() {
      self.is = "the best!"
  }
}

//Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.

import JacobTucker from 0x03

pub fun main(): String {
    return JacobTucker.is
}


<img width="553" alt="Screen Shot 2022-05-17 at 9 44 53 AM" src="https://user-images.githubusercontent.com/19650841/168827902-0a7eed1d-cbed-4318-9b32-5a4f6f384939.png">



Chapter 2 - Day 1

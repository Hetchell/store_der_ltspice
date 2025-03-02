# store_der_ltspice
LTSpice storage place

## How to use
The .asc files are runnable LTSpice files. Import into your appropriate folder and run via LTSpice. 
The user files are to be put into another folder in your documents/LTSpice folder, and that said folder's path included in LTSpice's other folders settings. If you don't know what that means, there are tutorials online to help you. Just search 'how to add extra components to LTSpice' and use the tutorial which talks about applying it to non-LTSpice internal folders. DO NOT MODIFY the original LTSpice's folders. 
The asy and TL431 txt files may be put into another folder. Be sure however to put this folder in the documents/LTSpice folder, or LTSpice can't find the model and throws an error. 

## Caution
Some files may throw defcon 2 errors. If you intend to fix them, good luck. You may want to search up 'convergence errors' in the internet. The hint may be having to implement series resistances in capacitors and voltage sources, since LTSpice prefers current sources for solution stability. 

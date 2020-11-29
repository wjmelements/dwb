Dragon Warrior Monsters Breeding DB
===================================
Terminal tools for Dragon Warrior Monsters breeding.
## Install
Clone this repo and add it to your path
## Usage
### dwb
`dwb` finds all pairs that match
```
$ dwb MedusaEye
water:Gamanian = Aquarella + MedusaEye
devil:AgDevil = MedusaEye + AnyDragon
devil:MedusaEye = MedusaEye + AnyZombie
devil:MedusaEye = 1EyeClown + AnyZombie
devil:MedusaEye = Gremlin + AnyZombie
devil:MedusaEye = AnyDevil + AnyDragon
devil:Grendal = MedusaEye + AnyBeast
dragon:Orochi = Andreal + MedusaEye
dragon:Orochi = GreatDrak + MedusaEye
```
### costs
`costs` shows the total number of "AnyFamily" monsters required to breed the mosters using the provided db.
By excluding the water db you can get costs for Terry in the original.
```
$ ./costs db/*
```
### perm
`perm` was a tool for expanding my original dataset.
It can be removed but would be useful for expanding multiple combinations into separate lines.

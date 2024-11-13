# Elliptic Curve Pairings From Scratch

toy example of ec pairing over bls12-381 in an effort to learn about optimizations

initial draft is a near copy of [ethereum/py_ecc](https://github.com/ethereum/py_ecc), simplified,
removed generics to only be used for bls12-381, & simplified the type system

helpful documents:

- [BLS12-381 For The Rest of Us](https://hackmd.io/@benjaminion/bls12-381)
- [Exploring Elliptic Curve Pairings](https://medium.com/@VitalikButerin/exploring-elliptic-curve-pairings-c73c1864e627)
- [(PDF) Pairings for Beginners](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf) (very thorough)

helpful implementations:

- [ethereum/py_ecc](https://github.com/ethereum/py_ecc)
- [ewynx/noir_bls12_31_pairing](https://github.com/ewynx/noir_bls12_381_pairing)

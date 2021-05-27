```jsx
<button onClick={() => setModalIsOpen(true)}>
  Show the only one and best Modal ever build!
</button>

<InfoModal
  modalIsOpen={false}
  character={{
    name: 'Bulbasaur',
    id: 1,
    type: 'Grass',
    description:
      'A strange seed was planted on its back at birth.The plant sprouts and grows with this POKéMON.',
    image:
      'https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1',
  }}
  hideModal={() => setModalIsOpen(false)}
/>
```

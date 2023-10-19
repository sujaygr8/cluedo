# Cluedo Game Checklist

## Suspects

- [ ] Miss Scarlett <input type="checkbox" id="scarlett" onclick="toggleCheckbox('scarlett')">
- [ ] Colonel Mustard <input type="checkbox" id="mustard" onclick="toggleCheckbox('mustard')">
- [ ] Mrs. White <input type="checkbox" id="white" onclick="toggleCheckbox('white')">
- [ ] Mr. Green <input type="checkbox" id="green" onclick="toggleCheckbox('green')">
- [ ] Mrs. Peacock <input type="checkbox" id="peacock" onclick="toggleCheckbox('peacock')">
- [ ] Professor Plum <input type="checkbox" id="plum" onclick="toggleCheckbox('plum')">

## Rooms

- [ ] Hall <input type="checkbox" id="hall" onclick="toggleCheckbox('hall')">
- [ ] Lounge <input type="checkbox" id="lounge" onclick="toggleCheckbox('lounge')">
- [ ] Dining Room <input type="checkbox" id="dining" onclick="toggleCheckbox('dining')">
- [ ] Kitchen <input type="checkbox" id="kitchen" onclick="toggleCheckbox('kitchen')">
- [ ] Ballroom <input type="checkbox" id="ballroom" onclick="toggleCheckbox('ballroom')">
- [ ] Conservatory <input type="checkbox" id="conservatory" onclick="toggleCheckbox('conservatory')">
- [ ] Billiard Room <input type="checkbox" id="billiard" onclick="toggleCheckbox('billiard')">
- [ ] Library <input type="checkbox" id="library" onclick="toggleCheckbox('library')">
- [ ] Study <input type="checkbox" id="study" onclick="toggleCheckbox('study')">

## Weapons

- [ ] Candlestick <input type="checkbox" id="candlestick" onclick="toggleCheckbox('candlestick')">
- [ ] Dagger <input type="checkbox" id="dagger" onclick="toggleCheckbox('dagger')">
- [ ] Lead Pipe <input type="checkbox" id="leadpipe" onclick="toggleCheckbox('leadpipe')">
- [ ] Revolver <input type="checkbox" id="revolver" onclick="toggleCheckbox('revolver')">
- [ ] Rope <input type="checkbox" id="rope" onclick="toggleCheckbox('rope')">
- [ ] Spanner <input type="checkbox" id="spanner" onclick="toggleCheckbox('spanner')">

<script>
function toggleCheckbox(id) {
  var checkbox = document.getElementById(id);
  checkbox.checked = !checkbox.checked;
}
</script>

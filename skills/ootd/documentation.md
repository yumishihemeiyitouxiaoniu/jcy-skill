# ootd Skill Documentation

## Definition
The ootd (Outfit of the Day) skill allows users to share their outfit choices as a form of personal style expression and community engagement.

## Methods
- **getOutfit()**: Retrieves the current outfit of the user.
- **submitOutfit(outfitDetails)**: Submits a new outfit with details.
- **deleteOutfit(outfitId)**: Deletes a specified outfit by ID.

## Precautions
- Ensure that user data privacy is respected when sharing outfits.
- Community guidelines must be adhered to in submission methods.

## Best Practices
- Encourage users to provide stylish and appropriate outfit examples.
- Maintain an up-to-date list of accepted clothing styles.

## Examples
### Submitting an Outfit
```javascript
const outfit = {
  top: 'Blue Sweater',
  bottom: 'Black Jeans',
  shoes: 'White Sneakers'
};
submitOutfit(outfit);
```

### Retrieving an Outfit
```javascript
const currentOutfit = getOutfit();
console.log(currentOutfit);
```

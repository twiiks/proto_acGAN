## proco_ACGAN

### Motivation
- How to avoid an afterimage?

### Approach #3
- Instead of transfering character itself, what about generating a character and applying user's hand-writting style with Domain transfer?


## Structure
- **fontto** : applying **reference** for Korean character, plus additional functions needed
- **reference** : implemented code for acGAN


## Limits
- Needs a lot of datasets to train the model and style
- Requires 4~5 hours per user's own style to learn imply the model


## Example & Screenshot
![screenshot1](https://s3.ap-northeast-2.amazonaws.com/fontto/repository-images/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA+2017-10-24+%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE+10.17.31.png)

## Reference
> [zi2zi](https://github.com/kaonashi-tyc/zi2zi)

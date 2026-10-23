# NFL Big Data Bowl 2027

Our entry for the [NFL Big Data Bowl 2027](https://www.kaggle.com/competitions) on Kaggle.

## Team
- Mika Ismayilov ([@MikaIsmayilov](https://github.com/MikaIsmayilov))
- Steven Marathias ([@Stevenmarathias](https://github.com/Stevenmarathias))

## Getting started
1. Clone the repo
   ```bash
   git clone https://github.com/MikaIsmayilov/BigDataBowl2027.git
   cd BigDataBowl2027
   ```
2. Download the competition data from Kaggle into `data/`. This folder is git-ignored because the tracking files are too large to commit.
   ```bash
   kaggle competitions download -c <competition-slug> -p data/
   ```

## Structure
```
data/        # raw Kaggle data (not committed)
notebooks/   # exploration and analysis
src/         # reusable code
```

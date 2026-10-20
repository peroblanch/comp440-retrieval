# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Owen Blanchard
**Date:** 2026-10-20

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

On questions that name a character or something specific, TF-IDF will be better at matching.

### Vague descriptions: which method will do better, and why?

On vague descriptions and 'vibe' matchings, embeddings will have underlying values that succeed.

## Part 1: Build the TF-IDF model

### The settings you chose, and why

REMOVE_STOP_WORDS = True: Stop words have no semantic value, aren't interesting or helpful, and will appear frequently across movie descriptions if not removed.
MIN_MOVIES = 1: both systems should be able to handle extremely infrequent words that only appear in one movie, but there could be value in identifying movies based on prompts relevant only to that movie.
REPEATS_COUNT_LESS = True: This is a fundamental part of TF-IDF, and making it less sensitive to repeat words is an important part of the algorithms functionality.

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

XXXX

## Part 3: Your own searches

### Your questions, as you typed them

XXXX

### Did the movies you meant come up? What did TF-IDF get right and wrong?

XXXX

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

XXXX

### The misses you looked at: what do they have in common?

XXXX

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX

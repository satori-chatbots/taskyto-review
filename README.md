# Taskyto

Taskyto is a chatbot development framework. It is based on describing the tasks that a chatbot needs to perform using the notion of chatbot module. There are several kinds of modules like: menu, data gathering, action, sequence.

## Evaluation (CUI'24)

We have evaluated Taskyto across several dimensions. The results of the evaluation are available [here](evaluation/README.md).

## Usage

To run a specific chatbot there is a script (`main.py`) which is in charge of loading the chatbot and interpret the contents of the yaml files. The yaml files must be located in some folder. For example, `examples/yaml/bike-shop`. Then:

```
python src/main.py --chatbot examples/yaml/bike-shop/
```

## Configuration

API keys can be set as environment variables or in a `keys.properties` files.
The most important API key is `OPENAI_API_KEY`.

The `keys.properties` has the following form:

```
[keys]
SERPAPI_API_KEY=anapiforgooglesearch
OPENAI_API_KEY=theopenaikey
```

## Examples

The `examples/yaml` folder contains several examples developed with Taskyto:

 * bike-shop
 * photography
 * pizza-shop  
 * smart_calculator  
 * song-recommender  
 * travel-booking  
 * veterinary_center


# run-openmcx
A composite github action to ease runing simulations in the open source simulator openmcx

## Usage

Use this github action in a github actions pipeline as follows:
```
steps:
  - name: run openmcx
    uses: localhorst87/run-openmcx@v0.2.0
    with: 
      ssd: ./path/to/your/system_1.ssd ./path/to/another/arbitrary_system.ssd
      resultDir: ./folder/where/results/shall/be/stored
```

For detailed specification of inputs and the output structure, see the meta-data in the [action YAML](./action.yml).

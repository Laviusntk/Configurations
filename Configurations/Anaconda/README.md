<h1 align="center">Anaconda Configurations</h1>
<p align="center">
    This folder contains my commonly used configurations.
</p>

## Configurations
<blockquote>
<p>

💡 "Give me six hours to chop down a tree and I will spend the first four sharpening the axe."

</p>
</blockquote>


<blockquote>

| Configuration | Description                                 | Docs                                     |
| ------------  | ------------------------------------------- | -------------------------------          |
|                                 |
| Data Science | An Anaconda Environment Containing AI/Data Science Tools/Packages | [Docs](./anaconda_ai_tools_environment.yaml) |

</blockquote>


### Data Science Tools
<br>

```
conda create --name datascience
conda activate data datascience
conda env update --file anaconda_ai_tools_environment.yaml
```
<h1 align="center">Anaconda Configurations</h1>
<p align="center">
    This folder contains my commonly used configurations.
</p>

## Configurations
<br>


| Configuration | Description                                 | Docs                                     |
| ------------  | ------------------------------------------- | -------------------------------          |
|                                 |
| 1. Data Science | An Anaconda Environment Containing AI/Data Science Tools/Packages | [Docs](./anaconda_ai_tools_environment.yaml) |

<br>

## 1. Data Science Configuration

Run these commands to setup the configuration

```bash
conda create --name datascience
conda activate data datascience
conda env update --file anaconda_ai_tools_environment.yaml
```

or 

```bash
git clone https://github.com/Laviusntk/Configurations.git

cd Configurations/Anaconda
sh SetupCondaAIEnvironment.sh
```
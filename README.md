[![atthealchemist's GitHub stats](https://github-readme-stats.vercel.app/api?username=atthealchemist&show_icons=true&hide=stars&include_all_commits=true)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=atthealchemist)](https://github.com/anuraghazra/github-readme-stats)

*NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats.*

## About me

```python
import attr
from typing import List, Dict


@attr.s(frozen=True, auto_attribs=True)
class MeAsPythonDeveloper:
    position: str = "Middle-To-Senior"  # as i think
    python_version: str = "^3.8"
    experience_years: int = 5
    stack: List[str] = [
        "Django 3.0+ / Django REST Framework",
        "FastAPI",
    ]
    use_ipython: bool = True
    use_jupiter_notebooks: bool = True  # ❤️
    use_async: bool = True
    use_pydantic: bool = True
    testing_framework: str = "pytest"
    testing_abilities: List[str] = [
        "Mocking",
        "Parametrized testing",
        "Fixtures"
    ]
    dependency_management: List[str] = [
        "pip requirements.txt",
        "pipenv",
        "poetry"  # favourite
    ]
    extras: Dict = {
        "refactoring": True,
        "dev_methodology": [
            "TDD", 
            "TDD mixed with FDD",
            "RAD",
        ]
    }

```

```javascript
const meAsFrontendDeveloper = {
    languageVersion: "ES 2016", 
    experience: "~ 4 years",
    defaultFramework: "React.js",
    useTypescript: false,  // Don't like syntax sugar-like static typing everywhere (not related to Python tho)
    scss: false,  // and another preprocessors
    redux: false,
    useHooks: true,
    useNextJs: true,
    classesStyle: "arrow-like"
};
```

```sql
<!-- ME AS DATABASE USER -->
USE DATABASE ENGINE POSTGRESQL VERSION 12.1+;
DECLARE FAVOURITE_DB CONSTANT varchar DEFAULT "POSTGRESQL";
```

```yaml
me_as_devops:
    docker:
        docker-compose: true
        creating-own-images: true
        creating-dockerfile: true
```

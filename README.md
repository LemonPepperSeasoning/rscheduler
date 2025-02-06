[![PyPi](https://img.shields.io/pypi/v/rscheduler)](https://pypi.org/project/rscheduler/)
[![GitHub actions status](https://github.com/lemonpepperseasoning/rscheduler/workflows/CI/badge.svg)](https://github.com/lemonpepperseasoning/rscheduler/actions/workflows/CI.yml)

# rscheduler

python scheduling library implemented in rust

### Project setup

```
python3 -m venv venv
source venv/bin/activate
pip install maturin
maturin develop
```

### Run

```
maturin develop
python3

>> import rscheduler
>> rscheduler.schedule()
```

### Test

```
cargo test
```

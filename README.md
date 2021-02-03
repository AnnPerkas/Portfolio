# Telecom Project

The datasets contain data on the use of the virtual telephony service CallMeMaybe. Its clients are organizations that need to distribute large numbers of incoming calls among various operators or make outgoing calls through their operators. Operators can also make internal calls to communicate with one another. These calls go through CallMeMaybe's network.

The dataset `telecom_dataset_us.csv` contains the following columns:

- `direction` — call direction (`out` for outgoing, `in` for incoming)
- `internal` — whether the call was internal (between a client's operators)**
- `operator_id` — operator identifier
- `is_missed_call` — whether the call was missed
- `date` — date the statistics were retrieved
- `user_id` — client account ID
- `calls_count` — number of calls
- `call_duration` — call duration (excluding waiting time)
- `total_call_duration` — call duration (including waiting time)

 

The dataset `telecom_clients_us.csv` has the following columns:

- `tariff_plan` — client's current plan
- `date_start` — client's registration date

# Libaries Used:

_pandas,
numpy,
matplotlib,
seaborn,
plotly,
math,
scipy,scikit-learn_


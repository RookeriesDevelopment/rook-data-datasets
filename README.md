# ROOK-DATASETS

Last update: 2025-08-28

##
In this [repository](https://github.com/RookeriesDevelopment/rook-data-datasets), you can find examples of the data structures that ROOK manages, grouped by the data source that provides the information. In this version, we have data from Fitbit, Oura, Whoop, Garmin, Polar, Withings, Apple Health, Health Connect, Android.

### Available Data Structures
The detailed definitions of each of the structures are provided in the [ROOK](https://docs.tryrook.io/docs/rookconnect/data-structure) documentation. With regard to the information available in this repository, the following data can be found:



<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow" rowspan="2">Health Pilar</th>
    <th class="tg-c3ow" rowspan="2">Data Structure</th>
    <th class="tg-c3ow" colspan="9">Source of Data</th>
  </tr>
  <tr>
    <th class="tg-c3ow">Fitbit</th>
    <th class="tg-c3ow">Oura</th>
    <th class="tg-c3ow">Whoop</th>
    <th class="tg-c3ow">Garmin</th>
    <th class="tg-c3ow">Polar</th>
    <th class="tg-c3ow">Withings</th>
    <th class="tg-c3ow">Apple Health</th>
    <th class="tg-c3ow">Health Connect</th>
    <th class="tg-c3ow">Android</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow" rowspan="10">Body Health</td>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Body Metrics Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Heart Rate Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Oxygenation Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Nutrition Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✖️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Mood Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✖️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Hydration Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✖️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Blood Glucose Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Blood Pressure Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>

  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Temperature Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Body Summary</a></td>
    <td class="tg-c3ow">✔️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✔️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✔️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="7">Physical Health</td>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Activity Event</a></td>
    <td class="tg-c3ow">✔️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✔️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✔️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Heart Rate Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Oxygenation Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Stress Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✖️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✖️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Steps Event</a></td>
    <td class="tg-c3ow">✔️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✔️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✔️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Calories Event</a></td>
    <td class="tg-c3ow">✖️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✖️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✖️</td> <!-- Garmin -->
    <td class="tg-c3ow">✖️</td> <!-- Polar -->
    <td class="tg-c3ow">✖️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Physical Summary</a></td>
    <td class="tg-c3ow">✔️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✖️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✔️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
  <tr>
    <td class="tg-c3ow">Sleep Health</td>
    <td class="tg-c3ow"><a href="https://docs.tryrook.io/api">Sleep Summary</a></td>
    <td class="tg-c3ow">✔️</td> <!-- Fitbit -->
    <td class="tg-c3ow">✔️</td> <!-- Oura -->
    <td class="tg-c3ow">✔️</td> <!-- Whoop -->
    <td class="tg-c3ow">✔️</td> <!-- Garmin -->
    <td class="tg-c3ow">✔️</td> <!-- Polar -->
    <td class="tg-c3ow">✔️</td> <!-- Withings -->
    <td class="tg-c3ow">✔️</td> <!-- Apple Health -->
    <td class="tg-c3ow">✔️</td> <!-- Health Connect -->
    <td class="tg-c3ow">✖️</td> <!-- Android -->
  </tr>
</tbody>
</table>

### Null Values
According to the JSON standard, the values null, empty objects, and empty arrays indicate that the data source does not provide information about the variable. In the case of finding values 0, these were provided by the data sources.

## How to Load Data Reports
As mentioned above, the previously mentioned structures are grouped by data source in JSON files. The basic components of each file are as follows:

+   data_structure: Indicates the name of the database, which influences the source from which the information was obtained.
+   version: Reflects the version of the ROOK API.
+   created_at: Date of creation of the data set.
+   body_health: Information related to the Body Health pillar.
+   physical_health: Information related to the Physical Health pillar.
+   sleep_health: Information related to the Sleep Health pillar.

### Python Example
In the following Python code, an example is presented of how to access a body summary, an activity event, and a sleep summary from the Fitbit data source.

```python
#!/usr/bin/env python
import json

dataset_name = 'ROOKConnect-Fitbit-dataset-v2.json'
with open(dataset_name) as f:
    data = json.load(f)

body_summary = data['body_health']['body_summaries'][0]
activity_event = data['physical_health']['activity_events'][0]
sleep_summary = data['sleep_health']['sleep_summaries'][0]
```
##
<b>Disclaimer:</b> <em>This dataset is automatically updated at the end of each month, which is why there may be slight differences compared to the ROOK API Reference. It is always recommended to refer to the API Reference to verify the correct structure of each component.</em>

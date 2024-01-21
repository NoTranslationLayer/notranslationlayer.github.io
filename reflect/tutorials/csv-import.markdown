---
layout: page
title: Importing from CSV
permalink: /reflect/tutorials/csv-import
---

Reflect supports importing your data from various sources, as long as it follows a particular format which we will describe in this tutorial.

## Motivating Example: Events

Suppose you've been logging your events for the last few days, months, or years, and you'd like to have this data in Reflect to correlate with all of your other metrics. Reflect has a CSV import tool that can help you with this task.

As an example, here is what your data may look like:

<img src="image-1.png" alt="events-csv" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

In Reflect you can import this data by first pressing ![gear](gear.png) at the top left of the **Reflect** tab.

In the **Settings** page, scroll down until you see **Import Reflections**. Click and choose your CSV file for import. Once the CSV file is processed, the CSV importer tool will appear.

<img src="IMG_1035.PNG" alt="import-tool" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

As you can see, the import tool has inferred the date column of the CSV. All imported data needs a date column to differentiate when your metrics were recorded. If the CSV tool cannot infer the date column, your data can't be imported. Please [reach out to us](mailto:contact@ntl.ai) if this happens! We want to support as many date and time formats as possible. If there are multiple date columns, for example one for when you start an activity and one for when it ends, you will be able to select which is used for the Reflection recorded date.

Next, you can select what the types are your columns are. For importing data, we currently only support Yes/No, Numbers, and Text.

<img src="IMG_1036.PNG" alt="import-choice" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

Once you've selected the type of each metric and given your imported data a Reflection name, click **Import** at the top right of the importer tool. After the import has finished, you can go to the **History** tab and find your historical data.

<img src="IMG_1037.PNG" alt="event-history" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

As you can see from the imported data, where there were empty values in the CSV, the importer tool created a Reflection with the corresponding values empty.

### Importing Additional Data

Suppose you have additional data of the same type. When you try to import a CSV matching what was imported before, the import tool recognizes this and provides you the option of importing **Event** reflections specifically:

<img src="IMG_1038.PNG" alt="re-import" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">
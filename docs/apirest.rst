########
API REST
########


get-list
========

Get full list of existing task::

    HTTP: GET /tb/api/get-list

**Parameters**::

    None

**Example response**::

    [
        {
            "uuid": "361d0ef4-c663-11ec-a81c-a9552d28665d",
            "id_name": "printData1",
            "name": "printind data",
            "type": "single",
            "max_instances": 1,
            "trigger_type": "interval",
            "trigger_interval_weeks": null,
            "trigger_interval_days": null,
            "trigger_interval_hours": null,
            "trigger_interval_minutes": null,
            "trigger_interval_seconds": 5.0,
            "task_app_name": "djTaskBrocker",
            "task_module_name": "testSingleReglament",
            "task_function_name": "Print",
            "execute": false
        },
        {
            "uuid": "e9cecc7e-c818-11ec-89d1-b98329cca7c2",
            "id_name": "demo_interval",
            "name": "Demo interval",
            "type": "single",
            "max_instances": 1,
            "trigger_type": "interval",
            "trigger_interval_weeks": null,
            "trigger_interval_days": null,
            "trigger_interval_hours": null,
            "trigger_interval_minutes": null,
            "trigger_interval_seconds": 5.0,
            "task_app_name": "djTaskBrocker",
            "task_module_name": "testSingleReglament",
            "task_function_name": "Print",
            "execute": false
        }
    ]


stop-job-by-name
================

Stop executing task::

    HTTP: POST /tb/api/stop-job-by-name

**Parameters**::

    'id_name': String (internal Task name)


**Example response**::

    ... writing ... keep calm ...

**Errors**::

    ... writing ... keep calm ...


start-job-by-name
=================

Start executing task::

    HTTP: POST /tb/api/start-job-by-name

**Parameters**::

    'id_name': String (internal Task name)

**Example response**::

    ... writing ... keep calm ...

**Errors**::

    ... writing ... keep calm ...


delete-task-job-by-name
=======================

Delete task from database::

    HTTP: POST /tb/api/delete-task-job-by-name

**Parameters**::

    'id_name': String (internal Task name)

**Example response**::

    ... writing ... keep calm ...

**Errors**:

    ... writing ... keep calm ...


... writing ... keep calm ...
=============================

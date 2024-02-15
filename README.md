# Apache Airflow

[![PyPI version](https://badge.fury.io/py/apache-airflow.svg)](https://badge.fury.io/py/apache-airflow)
[![GitHub Build](https://github.com/apache/airflow/workflows/Tests/badge.svg)](https://github.com/apache/airflow/actions)
[![Coverage Status](https://codecov.io/gh/apache/airflow/graph/badge.svg?token=WdLKlKHOAU)](https://codecov.io/gh/apache/airflow)
[![License](https://img.shields.io/:license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/apache-airflow.svg)](https://pypi.org/project/apache-airflow/)
[![Docker Pulls](https://img.shields.io/docker/pulls/apache/airflow.svg)](https://hub.docker.com/r/apache/airflow)
[![Docker Stars](https://img.shields.io/docker/stars/apache/airflow.svg)](https://hub.docker.com/r/apache/airflow)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/apache-airflow)](https://pypi.org/project/apache-airflow/)
[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/apache-airflow)](https://artifacthub.io/packages/search?repo=apache-airflow)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Twitter Follow](https://img.shields.io/twitter/follow/ApacheAirflow.svg?style=social&label=Follow)](https://twitter.com/ApacheAirflow)
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://s.apache.org/airflow-slack)
[![Contributors](https://img.shields.io/github/contributors/apache/airflow)](https://github.com/apache/airflow/graphs/contributors)
[![OSSRank](https://shields.io/endpoint?url=https://ossrank.com/shield/6)](https://ossrank.com/p/6)

<picture width="500">
  <img
    src="https://github.com/apache/airflow/blob/19ebcac2395ef9a6b6ded3a2faa29dc960c1e635/docs/apache-airflow/img/logos/wordmark_1.png?raw=true"
    alt="Apache Airflow logo"
  />
</picture>

**Apache Airflow** adalah platform sumber terbuka yang digunakan untuk mengelola, menjadwalkan, dan mengawasi alur kerja (_workflows_) data. Dikembangkan oleh **_Apache Software Foundation_**, **Apache Airflow** memungkinkan pengguna untuk mendefinisikan, menjadwalkan, dan mengeksekusi alur kerja data yang kompleks secara terstruktur.

Beberapa fitur utama dari **Apache Airflow** meliputi:

1. **DAGs (Directed Acyclic Graphs)**: **Airflow** memanfaatkan DAGs untuk mewakili dan menjadwalkan alur kerja. DAG adalah grafik arah yang tidak memiliki siklus, yang menggambarkan langkah-langkah yang harus diambil dalam alur kerja secara berurutan.

2. **Scheduler**: **Airflow** dilengkapi dengan scheduler bawaan yang memungkinkan pengguna menjadwalkan dan mengeksekusi tugas-tugas pada waktu yang diinginkan.

3. **Executor**: **Airflow** mendukung berbagai executor yang dapat diintegrasikan dengan sistem manajemen sumber daya, seperti Celery atau LocalExecutor, untuk mendistribusikan dan menjalankan tugas.

4. **Operator**: **Operator** adalah unit eksekusi dalam DAG, mewakili tugas-tugas spesifik yang harus dilakukan. **Airflow** menyediakan berbagai operator bawaan untuk berbagai tugas, dan pengguna dapat membuat operator khusus sesuai kebutuhan.

5. **Web UI**: **Airflow** memiliki antarmuka pengguna berbasis web yang memungkinkan pengguna untuk memantau, mengelola, dan melacak progres alur kerja secara visual.

6. **Logging dan Monitoring**: **Airflow** menyediakan sistem logging yang kuat dan memungkinkan integrasi dengan alat monitoring eksternal.

**Airflow** umumnya digunakan dalam konteks pemrosesan dan analisis data besar, di mana alur kerja yang kompleks perlu diatur dan dijalankan secara otomatis. Dengan menggunakan **Airflow**, pengguna dapat membuat alur kerja yang dapat diulang, mudah dielus, dan mudah dipantau.

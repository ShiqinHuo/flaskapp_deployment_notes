# flaskapp_deployment_notes

### Structure of the flaskapp - v_0.1

<div class="highlight-none notranslate"><div class="highlight"><pre><span></span>root/
├── flaskapp/
│   ├── app.py
│   ├── db.py
│   ├── robot.txt
│   ├── auth.py
│   ├── video.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   └── video/
│   │       ├── create.html
│   │       ├── index.html
│   │       └── update.html
│   └── static/
│       └── style.css
├── voice_identification/
│   ├── cfg/
│   ├── data/
│   │   ├── model/
│   │   │   ├── weights.h5
│   │   ├── wav/
│   │   │   ├── enroll/
│   │   │   │   ├── 19-227-0000.wav
│   │   │   │   ├── 26-495-0000.wav
│   │   │   │   ├── 27-123349-0000.wav
│   │   │   ├── test/
│   │   │   │   ├── 19-198-0001.wav
│   │   │   │   ├── 27-123349-0001.wav
│   ├── constants.py
│   ├── model.py
│   ├── scoring.py
│   ├── sigproc.py
│   ├── wav_reader.py
├── tests/
│   ├── config_test.py
│   ├── data.sql
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_video.py
├── picture/
├── .virtualenvs/
│   ├── bin/
│   ├── lib/python3.6/site-packages/
│   ├── pip-selfcheck.json
│   ├── pyvenv.cfg
├── setup.py
</pre></div>
</div>

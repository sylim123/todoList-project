# todo

# 가상환경에서 사용했습니다.
virtualenv --python=python3.5 myvenv

source myvenv/bin/activate # 가상환경 실행

pip install django~=2.0

git clone https://github.com/sylim123/todo.git

cd todo

python manage.py migrate

python manage.py runserver 0.0.0.0:8000

# 서버 실행 후 127.0.0.1:8000 에서 실행하시면 됩니다.
git clone https://github.com/DingChuanV/clickhouse-driver.git
cd clickhouse-driver
pip install wheel
python setup.py bdist_wheel
cd dist
pip install clickhouse_driver-0.2.7-cp311-cp311-macosx_10_9_universal2.whl --no-deps
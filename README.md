# Инструкция по запуску

1. необходимо скачать [датасет](https://www.kaggle.com/c/home-credit-default-risk) и разархивировать его в папку `/data/raw`. В итоге в `/data/raw` должны присутствовать файлы:
   1. `application_test.csv`
   2. `application_train.csv`
   3. `bureau.csv `
   4. `bureau_balance.csv `
   5. `credit_card_balance.csv `
   6. `HomeCredit_columns_description.csv `
   7. `installments_payments.csv `
   8. `POS_CASH_balance.csv `
   9. `previous_application.csv `
   10. `sample_submission.csv`
2. необходимо иметь установленный `python3`
3. желательно использовать виртуальную среду python
4. необходимо загрузить использующиеся библиотеки с помощью команды `pip3 install -r requirements.txt`
5. для просмотра файла .ipynb используется `Jupyter Notebook`. Для его запуска необходимо выполнить команду `jupyter notebook`
6. все модели сохраняются в папку `/notebooks/HW#2_models`
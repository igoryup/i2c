# i2c
i2c master для платы de0 nano.
Для проверки работы протокола был считан серийный номер акселерометра.
Особенность этого акселерометра в том, что шина i2c "объединена" с SPI, и чтобы выбрать передачу данных по i2c нужно поднять CS в единицу.

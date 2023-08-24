# Программатор Modbus пультра WB-MIR v2 с помощью ПР-200
  Простой программатор универсального инфракрасного пульта с Modbus от WirenBoard. Программа для Овен ПР200 работает через holding регистры 5500-5502, так как Owen Logic не поддерживает регистры типа Coil с номером больше 4095. Реализованы только запись и воспроизведение команд в ячейках с вводимым номером. Дополнительно показывается статус устройства на шине RS485 и состояние дискретного входа (1w). 

  Ссылка на документацию по модулю WB-MIRv2 https://wirenboard.com/wiki/WB-MSx_Consumer_IR_Manual

  В качестве комментария содержится описание набора команд для моего кондиционера Dexp.

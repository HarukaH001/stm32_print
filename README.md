stm32_print

stm32 f767zi print library (USART3)

import .c to src directory -> include -> use

USART3:
Serial.print("Hello");  -> output: Hello
Serial.println("Hello"); -> output: Hello\r\n
Serial.printc('x'); -> output: x
Serial.getch() -> return char input

ANY:
print(&huartx,"Hello");  -> output: Hello
println(&huartx,"Hello"); -> output: Hello\r\n
printc(&huartx,'x'); -> output: x
getch(&huartx,) -> return char input
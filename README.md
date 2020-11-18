# Отчёт о тестировании приложения Precision

## Краткое описание
  18.11.2020г.
 Проведенно тестирование программы Precision, а имеено нового модуля который отвечает за внедрение 
 дополнителнительного бонуса новым клиентам

## Описание тестов

Проведено функциональное тестирование нового модуля

Тестовые данные:

public class Main {
  
  public static void main(String[] args) {
    
    double regularBonus = 0.3;
    
    double specialBonus = 0.6;
    
    double totalBonus = regularBonus + specialBonus;
    
    System.out.println(totalBonus);
  
  }

}

## Результаты

1. 0% не успешных тестов, выявлена ошибка при сложении в  коде
2. https://github.com/TatianaHrip/Wo/issues/4

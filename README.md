# ErlangC_Pack
A set of Erlang C functions for contact centers and any industries related to queues handling.<p>
Набор функций Эрланга для контакт-центров а также любых отраслей, связанных с обслуживанием очередей.
<b>fn_MinMax</b><p>
<b>Eng</b> Supporting function. Applies minimum and maximum bounds to a value. Returns: Minimum in the case of Value is less than Minimum, Maximum in the case of Value is greater than Minimum, Value in the case of Value is in range [Minimum; Maximum].<p>
<b>Rus</b> Вспомогательная функцияю Применяет минимальную и максимальную границы к значению. Возвращает: Minimum, если Value меньше Minimum, Maximum, если Value больше Maximum, Value, если Value находится в диапазоне [Minimum; Maximum].<p>
<b>fn_ErlangB</b><p>
<b>Eng</b> Calculates the probability of the call being blocked, that is that all the trunks are in use and the caller will receive a busy signal asumming blocked call gets lost and doesn't wait in the queue. Allows fractional values for all arguments.<p>
<b>Rus</b> Вычисляет вероятность блокировки вызова, то есть того, что все соединительные линии заняты и вызывающий абонент получит сигнал «занято», предполагая, что заблокированный вызов теряется и не помещается в очередь. Допускает дробные значения всех аргументов.<p>
<b>fn_ErlangBExt</b><p>
<b>Eng</b> Calculates the Calculates the probability of the call being blocked, that is that all the trunks are in use and the caller will receive a busy signal, assuming that some of the blocked subscribers will immediately repeat the call attempt. Allows fractional values for all arguments.<p>
<b>Rus</b> Вычисляет вероятность вероятность блокировки вызова, то есть того, что все соединительные линии используются и вызывающий абонент получит сигнал «занято». Предполагается, что часть заблокированных абонентов немедленно повторят попытку дозвона. Допускает дробные значения всех аргументов.<p>
<b>fn_ErlangC</b><p>
<b>Eng</b> Calculates the probability of a call queuing, assuming that pending calls remain in the system until they can be processed. Allows fractional values for all arguments.<p>
<b>Rus</b> Вычисляет вероятность постановки звонка в очередь, предполагая, что неотвеченные вызовы остаются в системе до тех пор, пока их не удастся обработать. Допускает дробные значения всех аргументов.<p>
<b>fn_ServiceLevel</b><p>
<b>Eng</b> Calculates service level for the given parameters. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает уровень сервиса при заданных параметрах. Допускает дробные значения всех аргументов.<p>
<b>fn_Agents</b><p>
<b>Eng</b> Calculates the minimum number of agents required to meet the target service level. Allows fractional values for all arguments. The result returnes as an integer.<p>
<b>Rus</b> Рассчитывает минимальное количество агентов, необходимое для достижения целевого уровня сервиса. Допускает дробные значения всех аргументов. Результат возвращается в  виде целого числа.<p>
<b>fn_FractionalAgents</b><p>
<b>Eng</b> Calculates the exact number of agents required to achieve a target service level. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает точное количество агентов, необходимое для достижения целевого уровня сервиса. Допускает дробные значения всех аргументов.<p>
<b>fn_AbandonRate</b><p>
<b>Eng</b> Calculates the percentage of calls that will remain in the queue for more than a specified time. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает процент вызовов, которые будут находиться в очереди больше заданного времени. Допускает дробные значения всех аргументов.<p>
<b>fn_AverageWaitTime</b><p>
<b>Eng</b> Calculates the average time all calls spent in the queue. Allows fractional values for all arguments.<p>
<b>Rus</b> Вычисляет среднее время нахождения всех звонков в очереди. Допускает дробные значения всех аргументов.<p>
<b>fn_CallCapacity</b><p>
<b>Eng</b> Calculates the number of calls which can be handled by the given number of agents whilst still achieving the grade of service. Allows fractional values for all arguments<p>
<b>Rus</b> Рассчитывает количество вызовов, которые могут быть обработаны заданным количеством агентов, сохраняя при этом уровень обслуживания. Допускает дробные значения всех аргументов.<p>
<b>fn_QueueSize</b><p>
<b>Eng</b> Calculates the average queue size. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает среднюю величину очереди. Допускает дробные значения всех аргументов.<p>
<b>fn_QueueTime</b><p>
<b>Eng</b> Calculates the average queue time for those calls which will queue. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает среднее время ожидания для тех вызовов, которые попадут в очередь. Допускает дробные значения всех аргументов.<p>
<b>fn_ServiceTime</b><p>
<b>Eng</b> Calculates the average waiting time in which a given percentage of the calls will be answered. Allows fractional values for all arguments.<p>
<b>Rus</b> Рассчитывает среднее время ожидания, в течение которого будет отвечен определенный процент вызовов. Допускает дробные значения всех аргументов.<p>

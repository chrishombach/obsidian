Quelle: [[heise-webinar-microservices1]]

# Das Problem mit unit-tests
Zu granulare [[unit test]] machen [[refactoring]] schwierig. Wenn der [[code]] nach dem Refactoring das Richtige tut, der unit test dennoch rot ausschlägt, ist er wenig hilfreich.
Zwei Aren von Test:
	- *classical*: Man testet die gesamte Funktionsweise (das ganze Auto)
		- Kritik: -zu große Einheiten
					- Tests zu langsam
					- Feedback zu spät
					- Kein sauberes Design
	- *London*: Man testet die einzelnen Funktionsweisen (man baut den Motor aus)
	- Kritik: - Nutzen nur während der Implementierung
				- Hoher Wartungsaufwand
				- Refactoring wird schwieriger
				- Kein Vertrauen in Test Suite


![[Unit oder IntegrationsTest_220314_171449.jpg]]
[[integrationstest]]
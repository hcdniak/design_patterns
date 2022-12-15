# Proxy Design Pattern

<!--
@startuml
namespace unnamed {

        interface Account [[Account.html]] {
            {abstract} +withdraw(): void
            {abstract} +getAccountNumber(): void
        }

        class ATM [[ATM.html]] {
            +withdraw(): void
            +getAccountNumber(): void
        }

        class BankAccount [[BankAccount.html]] {
            +withdraw(): void
            +getAccountNumber(): void
        }

        class Main [[Main.html]] {
            {static} +main(String[]): void
        }

        Account <|.. ATM
        Account <|.. BankAccount
    }

    namespace unnamed {
        interface Account [[Account.html]] {
            {abstract} +withdraw(): void
            {abstract} +getAccountNumber(): void
        }
    }

    center footer UMLDoclet 2.0.20, PlantUML 1.2022.12
@enduml
-->
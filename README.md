# -ltima-vez
import java.util.*;

public class Escalonador {

    // Classe para representar um processo
    static class Processo {
        int id;
        int tempoExecucao;
        int tempoChegada;
        int prioridade;

        public Processo(int id, int tempoExecucao, int tempoChegada, int prioridade) {
            this.id = id;
            this.tempoExecucao = tempoExecucao;
            this.tempoChegada = tempoChegada;
            this.prioridade = prioridade;
        }
    }

    // Método para simular o algoritmo FCFS
    public static void FCFS(List<Processo> processos) {
        // Implementação do FCFS
    }

    // Método para simular o algoritmo SJF Não-Preemptivo
    public static void SJF_NaoPreemptivo(List<Processo> processos) {
        // Implementação do SJF Não-Preemptivo
    }

    // Adicione métodos para os outros algoritmos...

    public static void main(String[] args) {
        List<Processo> processos = new ArrayList<>();
        // Adicionar processos à lista

        // Chamar os métodos de escalonamento
        FCFS(processos);
        SJF_NaoPreemptivo(processos);
        // Chamar os outros métodos...
    }
}

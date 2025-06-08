# 🚀 comandos-linux-trabalho-g2

Repositório com comandos básicos Linux para criação, manipulação e transferência de arquivos, úteis para o trabalho do grupo 2.

---

## 📁 Comando: `mkdir` — Criar diretórios

```bash
mkdir ~/trabalho
mkdir ~/trabalho/relatorios
mkdir ~/trabalho/documentos
```

## 📝 Comando: `touch` — Criar arquivos vazios
```bash
touch ~/trabalho/relatorios/relatorio.txt
touch ~/trabalho/documentos/notas.txt
```

## 🖋️ Comando: `echo` — Escrever texto em arquivos
```bash
echo "Relatório de Trabalho\nData: 07/05/2025" > ~/trabalho/relatorios/relatorio.txt
echo "Notas Finais:\n- Estudo de caso: 85\n- Performance: 90" > ~/trabalho/documentos/notas.txt
```

## 🔒 Comando: `chmod` — Alterar permissões
```bash
chmod 644 ~/trabalho/relatorios/relatorio.txt
chmod 700 ~/trabalho/documentos/notas.txt
```

## 📄 Comando: `ls` — Listar arquivos com detalhes
```bash
ls -l ~/trabalho/relatorios/relatorio.txt
ls -l ~/trabalho/documentos/notas.txt
```

## 🔄 Comando: `scp` — Transferir arquivos entre máquinas
```bash
scp C:\Users\1130883\Downloads\arquivo_local.txt EDUARDO@191.252.109.103:~/trabalho/
scp EDUARDO@191.252.109.103:~/trabalho/documentos/notas.txt C:\Users\1130883\Downloads\
```

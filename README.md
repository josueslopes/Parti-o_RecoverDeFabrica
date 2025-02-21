# Parti-o_RecoverDeFabrica
##Criar Partição de Fabrica Recovery

Claro! Aqui está o conteúdo em formato README.md:


# Backup usando o wbAdmin

Nota: você pode criar o backup numa partição do próprio disco, por exemplo, o disco local D ou E. 

## Instruções

1. Tudo pronto, abra o PowerShell como administrador.
2. Copie o comando abaixo:

```powershell

   "wbAdmin start backup -backupTarget:E: -include:C: -allCritical -quiet"
   ```

3. **Importante:** A letra `E` no comando deve ser substituída pela letra da unidade que vai receber o backup. 

   Por exemplo, se você preferir usar a unidade `D`, a linha de comando ficaria:

```powershell
   
   "wbAdmin start backup -backupTarget:D: -include:C: -allCritical -quiet"
   ```

4. Pressione Enter e aguarde a conclusão do backup.

## Observações

- Certifique-se de que a unidade de destino tenha espaço suficiente para armazenar o backup.
- É recomendável verificar se há uma cópia recente dos dados antes de iniciar o processo de backup.


Sinta-se à vontade para fazer quaisquer ajustes ou pedir mais informações!

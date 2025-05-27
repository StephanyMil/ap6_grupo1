# Rastreabilidade e Análise de Consistência – US123

## Matriz de Rastreabilidade

| Requisito / User Story | Relacionado a | Descrição / Observações |
|------------------------|---------------|--------------------------|
| US123 - Recuperar Senha | RF05 - Login  | Deve existir login ativo para recuperar senha |
| US123 | Política de Segurança XYZ | Link de redefinição deve expirar em 30 minutos |
| US123 | UC02 - Autenticação        | Vínculo necessário para validação de e-mail |

---

## Análise de Consistência

- [x] O e-mail já é utilizado no cadastro?
- [ ] O formato do e-mail é validado antes do envio?
- [ ] Existe possibilidade de redefinir senha com autenticação adicional?
- [ ] O link de redefinição tem validade e uso único?

### Recomendações:

- Definir política de segurança para o link de redefinição.
- Incluir mensagem de confirmação para e-mails não cadastrados.
- Validar formato do e-mail no frontend e backend.

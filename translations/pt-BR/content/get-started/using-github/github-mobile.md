---
title: GitHub Mobile
intro: 'Faça triagem, colabore e gerencie seu trabalho em {% data variables.product.product_name %} do seu dispositivo móvel.'
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Mobile
redirect_from:
  - /get-started/using-github/github-for-mobile
  - /github/getting-started-with-github/github-for-mobile
  - /github/getting-started-with-github/using-github/github-for-mobile
---

## Sobre o {% data variables.product.prodname_mobile %}

{% data reusables.mobile.about-mobile %}

{% data variables.product.prodname_mobile %} oferece a você uma maneira de realizar trabalhos de alto impacto {% data variables.product.product_name %} rapidamente e de qualquer lugar. O {% data variables.product.prodname_mobile %}é uma maneira segura e confiável de acessar seus dados {% data variables.product.product_name %} através de um aplicativo cliente confiável e primordial.

Com o {% data variables.product.prodname_mobile %} você pode:

- Gerenciar, fazer triagem e limpar notificações
- Leia, analisar e colaborar em problemas e pull requests
- Pesquisar, navegar e interagir com usuários, repositórios e organizações
- Receber uma notificação push quando alguém mencionar seu nome de usuário
{% ifversion fpt or ghec %}- Proteja sua conta do GitHub.com com autenticação de dois fatores{% endif %}

Para mais informações sobre notificações para {% data variables.product.prodname_mobile %}, consulte "[Configurando notificações](/github/managing-subscriptions-and-notifications-on-github/configuring-notifications#enabling-push-notifications-with-github-mobile)."

## Instalar o {% data variables.product.prodname_mobile %}

Para instalar {% data variables.product.prodname_mobile %} para Android ou iOS, consulte [{% data variables.product.prodname_mobile %}](https://github.com/mobile).

## Gerenciar contas

You can be simultaneously signed into mobile with one personal account on {% data variables.product.prodname_dotcom_the_website %} and one personal account on {% data variables.product.prodname_ghe_server %}. Para obter mais informações sobre nossos diferentes produtos, consulte "[Produtos de {% data variables.product.company_short %}](/get-started/learning-about-github/githubs-products)"

{% data reusables.mobile.push-notifications-on-ghes %}

{% data variables.product.prodname_mobile %} pode não funcionar com a sua empresa se for necessário acessar sua empresa através da VPN.

### Pré-requisitos

Você precisa instalar {% data variables.product.prodname_mobile %} 1.4 ou superior no seu dispositivo para usar {% data variables.product.prodname_mobile %} com {% data variables.product.prodname_ghe_server %}.

Para usar {% data variables.product.prodname_mobile %} com {% data variables.product.prodname_ghe_server %}, {% data variables.product.product_location %} deve ser a versão 3.0 ou superior, e o proprietário da empresa deverá habilitar o suporte móvel para a sua empresa. Para obter mais informações, consulte {% ifversion ghes %}"[Observações de versão](/enterprise-server/admin/release-notes)e {% endif %}"[Gerenciando {% data variables.product.prodname_mobile %} para a sua empresa]({% ifversion not ghes %}/enterprise-server@latest{% endif %}/admin/configuration/configuring-your-enterprise/managing-github-mobile-for-your-enterprise){% ifversion not ghes %}" na documentação de {% data variables.product.prodname_ghe_server %}.{% else %}."{% endif %}

During the beta for {% data variables.product.prodname_mobile %} with {% data variables.product.prodname_ghe_server %}, you must be signed in with a personal account on {% data variables.product.prodname_dotcom_the_website %}.

### Adicionar, alternar ou encerrar a sessão das contas

You can sign into mobile with a personal account on {% data variables.product.prodname_ghe_server %}. Na parte inferior do aplicativo, mantenha pressionado {% octicon "person" aria-label="The person icon" %} **Perfil** e, em seguida, toque em {% octicon "plus" aria-label="The plus icon" %} **Adicionar Conta Corporativa**. Siga as instruções para efetuar o login.

After you sign into mobile with a personal account on {% data variables.product.prodname_ghe_server %}, you can switch between the account and your account on {% data variables.product.prodname_dotcom_the_website %}. Na parte inferior do aplicativo, mantenha pressionado {% octicon "person" aria-label="The person icon" %} **Perfil** e, em seguida, toque na conta para a qual você deseja mudar.

If you no longer need to access data for your personal account on {% data variables.product.prodname_ghe_server %} from {% data variables.product.prodname_mobile %}, you can sign out of the account. Na parte inferior do aplicativo, mantenha pressionado {% octicon "person" aria-label="The person icon" %} **Perfil**, deslize para a esquerda na conta para encerrar sessão e toque em **Encerrar sessão**.

## Idiomas compatíveis com {% data variables.product.prodname_mobile %}

{% data variables.product.prodname_mobile %} está disponível nos seguintes idiomas.

- English
- Japanese
- Português do Brasil
- Chinês simplificado
- Spanish

Se você configurar o idioma do seu dispositivo para um idioma compatível, {% data variables.product.prodname_mobile %} será o idioma-padrão. Você pode alterar o idioma para {% data variables.product.prodname_mobile %} no no menu **Configurações** de {% data variables.product.prodname_mobile %}.

## Gerenciando links universais para {% data variables.product.prodname_mobile %} no iOS

{% data variables.product.prodname_mobile %} ativa automaticamente o Universal Links para iOS. Quando você clica em qualquer link {% data variables.product.product_name %}, a URL de destino vai abrir em {% data variables.product.prodname_mobile %} em vez do Safari. Para obter mais informações, consulte [Universal Links](https://developer.apple.com/ios/universal-links/)  no site de desenvolvedor da Apple

Para desabilitar os links universais, mantenha qualquer link {% data variables.product.product_name %} pressionado e, em seguida, pressione **Abrir**. Toda vez que você clica em um link {% data variables.product.product_name %} no futuro, a URL de destino abrirá no Safari em vez do {% data variables.product.prodname_mobile %}.

Para reabilitar o Universal Links, mantenha pressionado qualquer link {% data variables.product.product_name %}, depois clique em **Abrir em {% data variables.product.prodname_dotcom %}**.

## Compartilhando feedback

Se você encontrar um erro em {% data variables.product.prodname_mobile %}, você pode nos enviar um e-mail para <a href="mailto:mobilefeedback@github.com">mobilefeedback@github.com</a>.

Você pode enviar solicitações de recursos ou outros feedbacks para {% data variables.product.prodname_mobile %} em [{% data variables.product.prodname_discussions %}](https://github.com/github/feedback/discussions?discussions_q=category%3A%22Mobile+Feedback%22).

## Desativando versões beta para iOS

Se você estiver testando uma versão beta do {% data variables.product.prodname_mobile %} para iOS usando TestFlight, você pode deixar a versão beta a qualquer momento.

1. Em seu dispositivo iOS, abra o app TestFlight.
2. Em "Apps", clique em **{% data variables.product.prodname_dotcom %}**.
3. Na parte inferior da página, clique em **Interromper testes**.

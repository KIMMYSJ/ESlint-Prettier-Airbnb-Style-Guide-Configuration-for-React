# ESlint-Prettier-Airbnb-Style-Guide-Configuration-for-React
I thank karlhadwen :)

1.Navigate to your app directory where you want to include this style configuration.
<code>cd my-app</code>

2.Run this command inside your app's root directory. Note: this command executes the eslint-prettier-config.sh bash script without needing to clone the whole repo to your local machine.

<code>exec 3<&1;bash <&3 <(curl https://raw.githubusercontent.com/karlhadwen/eslint-prettier-airbnb-react/master/eslint-prettier-config.sh 2> /dev/null)
</code>

# Gated Example Message

The next sentence only shows up if the user is authenticated:

<ClientOnly>
   <AuthOnly>
      <p>Shh this is a secret</p>
   </AuthOnly>
</ClientOnly>

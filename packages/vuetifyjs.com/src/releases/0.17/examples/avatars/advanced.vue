<template>
  <v-layout justify-center column>
    <v-subheader>Today</v-subheader>
    <v-expansion-panel>
      <v-expansion-panel-content hide-actions>
        <v-layout align-center row spacer slot="header">
          <v-flex xs1>
            <v-avatar size="36px" slot="activator">
              <img src="https://avatars0.githubusercontent.com/u/9064066?v=4&s=460" alt="">
            </v-avatar>
          </v-flex>
          <v-flex xs3>
            <strong>John Leider</strong>
          </v-flex>
          <v-flex no-wrap>
            <strong>Welcome to Vuetify.js!</strong>
            &nbsp;&mdash;
          </v-flex>
          <v-flex
            class="grey--text"
            ellipsis
          >
            Thank you for joining our community and for using Vuetify in your projects
          </v-flex>
        </v-layout>
        <v-card>
          <v-divider></v-divider>
          <v-card-text>
            Hello
          </v-card-text>
        </v-card>
      </v-expansion-panel-content>
      <v-expansion-panel-content hide-actions>
        <v-layout align-center row spacer slot="header">
          <v-flex xs1>
            <v-avatar size="36px" slot="activator">
              <v-icon color="red">people</v-icon>
            </v-avatar>
          </v-flex>
          <v-flex xs3>
            <strong class="red--text">Social</strong>&nbsp;<span class="grey--text">(3)</span>
          </v-flex>
          <v-flex>
            <v-chip label small color="red lighten-4" class="ml-0">1 new</v-chip>
            <strong>Twitter</strong>
          </v-flex>
        </v-layout>
        <v-card>
          <v-divider></v-divider>
          <v-card-text>
            Hello
          </v-card-text>
        </v-card>
      </v-expansion-panel-content>
      <v-expansion-panel-content hide-actions>
        <v-layout align-center row spacer slot="header">
          <v-flex xs1>
            <v-avatar size="36px" slot="activator">
              <v-icon color="cyan darken-1">local_offer</v-icon>
            </v-avatar>
          </v-flex>
          <v-flex xs3>
            <strong class="cyan--text text--darken-1">Promos</strong>&nbsp;<span class="grey--text">(4)</span>
          </v-flex>
          <v-flex xs3 no-wrap>
            <v-chip label small color="cyan lighten-4" class="ml-0">2 new</v-chip>
            <strong>Shop your way</strong>
            <span>, New deals available, Join Today</span>
          </v-flex>
        </v-layout>
        <v-card>
          <v-card-text>
            Hello
          </v-card-text>
        </v-card>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-layout>
</template>

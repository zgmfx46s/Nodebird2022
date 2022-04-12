<template>
  <div>
      <v-container>
        <v-card style="margin-bottom: 20px">
            <v-container>
                <v-subheader>내 프로필</v-subheader>
            </v-container>
            <v-form>
                <v-text-field
                    label= "이메일"
                    type:= "email"
                    required
                />
                <v-text-field
                    label= "비밀번호"
                    type:= "password"
                    required
                />
                <v-text-field
                    label= "비밀번호확인"
                    type:= "password"
                    required
                />
                <v-text-field
                    label= "닉네임"
                    type:= "nickname"
                    required
                />
            </v-form>
        </v-card>
      </v-container>
  </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'nuxt.js',
        }
    },
    head() {
        return {
            title: '프로필',
        }    
    }
}
</script>

<style>

</style>
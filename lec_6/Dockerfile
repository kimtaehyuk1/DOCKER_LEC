FROM ubuntu

# 30초 간격으로 특정 사이트 접속 체크, 응답 지연은 30초이내에 들어올때까지는 오류없음.
HEALTHCHECK --interval=30s --timeout=30s CMD [ "curl","-f","http://127.0.0.1","||","exit 1" ]
# 디비체크 예시
# HEALTHCHECK --interval=30s --timeout=30s CMD [ "mysqladmin","ping","-h","http://127.0.0.1","--password=12341234","--silent" ]
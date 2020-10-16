nameSRC = unity/unity.c\
src/factorial.c\
test/test_factorial.c\
main.c

INC = -Iunity\
-Iinc\
-Itest

PROJECT_NAME = FACTORIAL.out
BUILD = build
$(PROJECT_NAME): $(SRC)
	gcc $(SRC) $(INC) -o TEST_$(PROJECT_NAME)
all: $(SRC) $(BUILD)
	gcc $(SRC) $(INC) -o $(PROJECT_NAME)
run:$(PROJECT_NAME)
	./TEST_${PROJECT_NAME}
doc:
	make -C documentation

clean:
	rm -rf $(PROJECT_NAME) documentation/html
$(BUILD):
	mkdir build
